### Welcome to the Network Ecology Group GitHub repository!
---
<p align="center">
The Network Ecology Group at Newcastle University is an international team of researchers that combine advances in ecological network analysis with DNA-metabarcoding to examine the impacts of environmental change on species-interactions and ecosystem functioning. It is the development and application of complexity science that unites our work, with current projects examining the consequences of environmental change on the network structure and functioning of microbe, plant and animal communities, mainly within forest- and agro-ecosystems. We are also creating new tools and metrics for biomonitoring, as well as for assessing and designing restoration programmes in tropical and temperate ecosystems.
</p>


<p align="center">
  <img src="https://github.com/NewcastleUni-NetworkEcologyGroup/.github/blob/main/images/NEG_github.png" />
</p>

<p align="center">

![Total Repositories](https://img.shields.io/github/repo-count/NewcastleUni-NetworkEcologyGroup?style=flat-square) ![Total Stars](https://img.shields.io/github/stars/NewcastleUni-NetworkEcologyGroup?style=flat-square) ![Total Forks](https://img.shields.io/github/forks/NewcastleUni-NetworkEcologyGroup?style=flat-square) ![Total Contributors](https://img.shields.io/github/all-contributors/NewcastleUni-NetworkEcologyGroup?style=flat-square)![contributors](https://img.shields.io/badge/NewcastleUni-NetworkEcologyGroup-10%20contributors-blue.svg)

</p>

<p align="center">

![RStudio](https://img.shields.io/badge/RStudio-4285F4?style=for-the-badge&logo=rstudio&logoColor=white)![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

</p>

<!DOCTYPE html>
<html>
<head>
  <title>Organization Name - GitHub Profile</title>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js%22%3E</script>
</head>
<body>
  <h1>Organization Name</h1>

  <h2>Stats</h2>
  <div id="repositoriesCount"></div>

  <script>
    $(document).ready(function() {
      var orgName = 'organizationname'; // Replace with your actual organization name

      // Fetch organization data from GitHub API
      $.getJSON("https://api.github.com/orgs/" + orgName, function(data) {
        var repositoriesCount = data.public_repos;

        // Display the number of repositories
        $("#repositoriesCount").html("Total Repositories: " + repositoriesCount);
      });
    });
  </script>
</body>
</html>