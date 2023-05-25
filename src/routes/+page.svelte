<script>
  let name1 = "https://rickandmortyapi.com/api/character/119/name";
</script>

<div class="grid">
  <div class="card">
    <div class="image" />
    <div class="info">
      <h1 class="name">Evil Rick</h1>
      <h3 class="status">
        <div class="dead" />
         Dead - Humanoid
      </h3>

      <h3 class="locationLabel">Last known location</h3>
      <h3 class="location"><a href="#">Citadel of Ricks</a></h3>
    </div>
  </div>

  <div class="card">
    <div class="image2" />
    <div class="info">
      <h1 class="name">Glasses Morty</h1>
      <h3 class="status">
        <div class="alive" />
         Alive - Humanoid
      </h3>

      <h3 class="locationLabel">Last known location</h3>
      <h3 class="location"><a href="#">Citadel of Ricks</a></h3>
    </div>
  </div>

  <div class="card">
    <div class="image3" />
    <div class="info">
      <h1 class="name">Thomas Lipkip</h1>
      <h3 class="status">
        <div class="alive" />
         Alive - Humanoid
      </h3>

      <h3 class="locationLabel">Last known location</h3>
      <h3 class="location"><a href="#">Froopyland</a></h3>
    </div>
  </div>

  <div class="card">
    <div class="image4" />
    <div class="info">
      <h1 class="name">Bully</h1>
      <h3 class="status">
        <div class="unknown" />
         Unknown - Humanoid
      </h3>

      <h3 class="locationLabel">Last known location</h3>
      <h3 class="location"><a href="#">Earth - Replacement Dimension</a></h3>
    </div>
  </div>

  <div class="card">
    <div class="image5" />
    <div class="info">
      <h1 class="name">Albert Einstein</h1>
      <h3 class="status">
        <div class="dead" />
         Dead - Humanoid
      </h3>

      <h3 class="locationLabel">Last known location</h3>
      <h3 class="location"><a href="#">Earth - Replacement Dimension</a></h3>
    </div>
  </div>

  <div class="card">
    <div class="image6" />
    <div class="info">
      <h1 class="name">Agency Director</h1>
      <h3 class="status">
        <div class="dead" />
         Dead - Humanoid
      </h3>

      <h3 class="locationLabel">Last known location</h3>
      <h3 class="location"><a href="#">Earth - Replacement Dimension</a></h3>
    </div>
  </div>
</div>

<style>
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 30px;
  }

  .card {
    background: #333;
    overflow: hidden;
    height: 240px;
    display: flex;
    border-radius: 20px;
  }

  .image {
    width: 30%;
    background-image: url("https://rickandmortyapi.com/api/character/avatar/119.jpeg");
    background-size: cover;
    background-position: center;
  }
  .image2 {
    width: 30%;
    background-image: url("https://rickandmortyapi.com/api/character/avatar/143.jpeg");
    background-size: cover;
    background-position: center;
  }
  .image3 {
    width: 30%;
    background-image: url("https://rickandmortyapi.com/api/character/avatar/350.jpeg");
    background-size: cover;
    background-position: center;
  }
  .image4 {
    width: 30%;
    background-image: url("https://rickandmortyapi.com/api/character/avatar/509.jpeg");
    background-size: cover;
    background-position: center;
  }
  .image5 {
    width: 30%;
    background-image: url("https://rickandmortyapi.com/api/character/avatar/11.jpeg");
    background-size: cover;
    background-position: center;
  }
  .image6 {
    width: 30%;
    background-image: url("https://rickandmortyapi.com/api/character/avatar/9.jpeg");
    background-size: cover;
    background-position: center;
  }

  .info {
    padding-left: 20px;
    padding-right: 20px;
    padding-top: 10px;
    padding-bottom: 15px;
  }

  .dead {
    background: firebrick;
    width: 10px;
    height: 10px;
    border-radius: 100%;
    margin-right: 10px;
  }
  .alive {
    background: rgb(22, 214, 79);
    width: 10px;
    height: 10px;
    border-radius: 100%;
    margin-right: 10px;
  }

  .unknown {
    background: rgb(87, 87, 85);
    width: 10px;
    height: 10px;
    border-radius: 100%;
    margin-right: 10px;
  }

  .name {
    font-family: sans-serif;
    color: white;
  }

  .status {
    font-family: sans-serif;
    color: white;
    display: flex;
    align-items: center;
  }

  .locationLabel {
    color: #777;
    font-family: sans-serif;
    font-size: 16px;
    margin: 0 0 5px;
  }

  .location {
    color: white;
    font-family: sans-serif;
    font-size: 16px;
    margin-bottom: 20px;
    margin-left: 0;
    margin-right: 0;
    margin-top: 0;
    margin-bottom: 5px;
  }

  .location a {
    color: white;
    font-family: sans-serif;
    font-size: 16px;
    margin-bottom: 20px;
    margin-left: 0;
    margin-right: 0;
    margin-top: 0;
    margin-bottom: 5px;
  }
</style>
