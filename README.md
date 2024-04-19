<script>
document.addEventListener("DOMContentLoaded", function() {
  var elements = document.querySelectorAll('.fade-in');

  function fadeIn(elements, index) {
    if (index < elements.length) {
      elements[index].classList.add('show');
      
      setTimeout(function() {
        fadeIn(elements, index + 1);
      }, 2000); // Ajuste o tempo de atraso conforme desejado (em milissegundos)
    }
  }

  fadeIn(elements, 0);
});
</script>

<style>
.fade-in {
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
}

.fade-in.show {
  opacity: 1;
}
</style>

<!-- Adicione a classe "fade-in" a todo o texto -->
<p class="fade-in">#### Habilidades Técnicas: Excel, PowerBI, Python, Java, C#, C++, JavaScript, GDScript, CSS,Blender, AutoCAD, Unity, Godot, SketchUp, Clip Studio Paint, Adobe Premiere, Adobe Photoshop, CorelDRAW, BitBar</p>
<p class="fade-in">#### Idiomas: Português (Nativo) | Inglês (Fluente)</p>

<p class="fade-in">## Educação</p>
<ul class="fade-in">
  <li>Ensino Médio: E.E.E.B. Dolores Alcaraz Caldas, Porto Alegre, Rio Grande do Sul, Brasil (_2018_)</li>
  <li>Tecnólogo , Jogos Digitais: UniRitter, Porto Alegre, Rio Grande do Sul, Brasil (_2020 - Presente_)</li>
  <li>Certificação, Arquitetura de Nuvem do AWS: Atualmente completando a certificação AWS Academy Cloud Architecting (_Previsão de Conclusão: 2024_)</li>
</ul>

<p class="fade-in">## Experiência Profissional</p>
<p class="fade-in"><strong>Freelancer de Arte Digital, Especialista em Gráficos de Eventos, Administrativo | Mantovani Assessoria de Eventos (_Junho de 2022 - Presente_)</strong></p>
<ul class="fade-in">
  <li>Design de arte digital para diversas finalidades, desde identidade visual até materiais promocionais</li>
  <li>Desenvolvimento de visualizações de eventos em 3D realistas para comunicação eficaz durante as etapas de planejamento</li>
  <li>Otimização e criação de plantas baixas de eventos</li>
  <li>Participação ativa nas atividades administrativas, incluindo análise de dados, elaboração de planilhas, redigindo documentos e contratos.</li>
</ul>

<p class="fade-in"><strong>Operador de Caixa | Broto Saudável (_Janeiro de 2022 - Junho de 2022_)</strong></p>
<ul class="fade-in">
  <li>Prestação de atendimento ao cliente e gerenciamento de tele-entregas</li>
  <li>Análise e interpretação de dados para melhorar a eficiência operacional</li>
  <li>Trabalho próximo com membros da equipe para garantir uma experiência gastronômica positiva</li>
</ul>

<p class="fade-in"><strong>Operador de Caixa | Pizza D.O.C (_Junho de 2021 - Janeiro de 2022_)</strong></p>
<ul class="fade-in">
  <li>Operação como caixa e assistência em várias tarefas, incluindo preparo de pizzas e atividades de cozinha</li>
  <li>Adaptação rápida a novas responsabilidades e contribuição para um ambiente de trabalho dinâmico</li>
</ul>

<p class="fade-in"><strong>Equipe de Eventos | Mantovani Assessoria de Eventos (_Janeiro de 2017 - Março de 2020_)</strong></p>
<ul class="fade-in">
  <li>Colaboração com membros da equipe na montagem, planejamento e execução de eventos</li>
  <li>Utilização de habilidades criativas de resolução de problemas para superar desafios e cumprir prazos apertados.</li>
  <li>Desenvolvimento de fortes habilidades interpessoais por meio de interação constante com clientes e colegas.</li>
</ul>
