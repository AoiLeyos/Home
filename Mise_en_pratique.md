<style>

  .blue-text {
    color: blue;
  }

  .red-text {
    color: red;
  }

  .green-text {
    color: green;
  }

  .orange-text {
    color: orange
  }

  
  
</style>
<html lang=fr>
<h1 style="text-align: center;">Mise en Pratique</h1>

- Création du nouveau repository : gh repo create "Toto/Cheat_Seat"
    <p><img src="src\repo_create.png" alt="Création_of_repository_Cheat_Seat"></p>
- Clonage du repository : gh repo clone "Toto/Cheat_Seat"
    <p><img src="src\clone.png" alt="Clone_of_repository_Cheat_Seat"></p>
- Liste des pull requests ouvertes sur le repository : <html style="text-align: center;"> gh <span class="red-text">pr</span> list
    <p><img src="src\pr_list.png" alt="List_of_pull_request_in_repository"></p>
- Ouverture d'une nouvelle pull request: gh <span class="red-text">pr</span> create "<span class="orange-text">base branche_cible</span>" "<span class="orange-text">head branche_source</span>" "<span class="orange-text">title: 'Title_of_pr'</span>"
    <p><img src="" alt="New_Pull_request"></p>
- 