- 👋 Hi, I’m @jotagomez2
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
jotagomez2/jotagomez2 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<?php
    include "conexao.php";
    $conexao->query("DELETE FROM mm WHERE Nome=$_POST[Nome]");
?>

