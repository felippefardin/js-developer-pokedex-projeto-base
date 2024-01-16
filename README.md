# js-developer-pokedex-projeto-base

<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pokedex</title>

    <!-- Normalize CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css"
        integrity="sha512-NhSC1YmyruXifcj/KFRWoC561YpHpc5Jtzgvbuzx5VozKpWvQ+4nXhPdFgmx8xqexRcpAglTj9sIBWINXa8x5w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />

    <!-- Font Roboto -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;500;700&display=swap" rel="stylesheet">

    <!-- Nosso CSS -->
    <link rel="stylesheet" href="/assets/css/global.css">
    <link rel="stylesheet" href="/assets/css/pokedex.css">
</head>

<body>
    <section class="content">
        <h1>Pokedex</h1>

        <ol class="pokemons">
            <li class="pokemon">
                <span class="number">#001</span>
                <span class="name">Bulbasaur</span>

                <div class="detail">
                    <ol class="types">
                        <li class="type">grass</li>
                        <li class="type">poison</li>
                    </ol>

                    <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/1.svg"
                        alt="Bulbasaur">
                </div>
            </li>
        </ol>
    </section>

    <section class="content">
              <ol class="pokemons">
            <li class="pokemon">
                <span class="number">#002</span>
                <span class="name">Ivysaur</span>

                <div class="detail">
                    <ol class="types">
                        <li class="type">grass</li>
                        <li class="type">poison</li>
                    </ol>

                    <img class="ivysaur-imagem" src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/002.png"
                        alt="Ivysaur">
                </div>
            </li>
        </ol>
    </section>

    <section class="content">
        <ol class="pokemons">
      <li class="pokemon">
          <span class="number">#003</span>
          <span class="name">Venusaur</span>

          <div class="detail">
              <ol class="types">
                  <li class="type">grass</li>
                  <li class="type">poison</li>
              </ol>

              <img class="venusaur-imagem" src="https://i.pinimg.com/originals/37/3f/37/373f370183150947b55ca7b68248e447.png"
                  alt="Ivysaur">
          </div>
      </li>
  </ol>
</section>

<section class="content">
    <ol class="pokemons">
  <li class="pokemon">
      <span class="number">#004</span>
      <span class="name">Charmander</span>

      <div class="detail">
          <ol class="types">
              <li class="type">Fire</li>
            
        
          </ol>

          <img class="charmander-imagem" src="https://seeklogo.com/images/C/charmander-logo-62F7FE99A5-seeklogo.com.png"
              alt="Ivysaur">
      </div>
  </li>
</ol>
</section>

<section class="content">
    <ol class="pokemons">
  <li class="pokemon">
      <span class="number">#005</span>
      <span class="name">Charmeleon</span>

      <div class="detail">
          <ol class="types">
              <li class="type">Fire</li>
              
            
        
          </ol>

          <img class="charmeleon-imagem" src="https://seeklogo.com/images/C/charmeleon-logo-3C525A08C4-seeklogo.com.png"
              alt="charmeleon">
      </div>
  </li>
</ol>
</section>

<section class="content">
    <ol class="pokemons">
  <li class="pokemon">
      <span class="number">#006</span>
      <span class="name">Charizard</span>

      <div class="detail">
          <ol class="types">
              <li class="type">Fire</li>
              <li class="type">fly</li>
            
        
          </ol>

          <img class="charizard-imagem" src="https://seeklogo.com/images/C/charizard-logo-C9856A6142-seeklogo.com.png"
              alt="charizard">
      </div>
  </li>
</ol>
</section>



    <!-- Nosso JS -->
    <script src="/assets/js/main.js"></script>
</body>

</html>
