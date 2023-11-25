# Open Your World!

```html
<style>
  body { color: #8B00FF; } /* roxo */
  strong { color: #00FF00; } /* verde */
</style>

```csharp
using UnityEngine;

public class UserProfile : MonoBehaviour
{
    // Informações pessoais
    string idade = "<strong>21 anos</strong>";
    string localizacao = "<strong>Luanda, Angola</strong>";
    string inicioProgramador = "<strong>2018</strong>";

    // Educação
    string universidade = "<strong>Primeiro Ano de Engenharia de Computação</strong>";

    // Habilidades
    string[] idiomas = { "<strong>Português</strong>", "<strong>Inglês</strong>" };
    string[] desenvolvimentoSoftware = { "<strong>Unity</strong>", "<strong>Android Studio</strong>" };
    string desenvolvimentoFrontEnd = "<strong>Web</strong>";

    // Experiência Profissional
    string cargo = "<strong>Desenvolvedor Unity e Android Studio</strong>";
    string[] responsabilidades = {
        "<strong>Desenvolvimento de jogos em Unity 3D e 2D</strong>",
        "<strong>Criação de aplicativos com Android Studio</strong>"
    };

    void Start()
    {
        MostrarPerfil();
    }

    void MostrarPerfil()
    {
        Debug.Log("🎂 **Idade:** " + idade);
        Debug.Log("🌍 **Localização:** " + localizacao);
        Debug.Log("📅 **Início como Programador:** " + inicioProgramador);
        Debug.Log("\n## 📚 **Educação**");
        Debug.Log("🎓 **Universidade:** " + universidade);
        Debug.Log("\n## 🚀 **Habilidades**");
        Debug.Log("🗣️ **Idiomas:** " + string.Join(", ", idiomas));
        Debug.Log("💻 **Desenvolvimento de Software:** " + string.Join(", ", desenvolvimentoSoftware));
        Debug.Log("🌐 **Desenvolvimento Front-End:** " + desenvolvimentoFrontEnd);
        Debug.Log("\n## 💼 **Experiência Profissional**");
        Debug.Log("👨‍💻 **" + cargo + "**");
        
        foreach (string responsabilidade in responsabilidades)
        {
            Debug.Log("  - " + responsabilidade);
        }
    }
}



 
 <h2>Tools & Technologies </h2>
<p>
   <br>
 [unity](https://github.com/elisioMassaqui/elisioMassaqui/assets/145590545/a88ee5b6-71e2-4376-96c1-bb22a40c25e3)
</p><br>

- 
<!---
elisioMassaqui/elisioMassaqui is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
