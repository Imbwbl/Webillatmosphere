<script>
  import Logo from "./assets/logo.png";
</script>

<main>
  <div class="box">
    <div class="title-box">
      <img class="logo" src={Logo} alt="Logo" />
      <h1 class="title">Vanillatmoshere</h1>
    </div>
    <div class="download-box">
      <a
        class="button-1"
        href="https://github.com/pinokaille/Vanillatmosphere/releases/latest"
      >
        Download Latest
      </a>
    </div>
  </div>
</main>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Cherry+Bomb+One&display=swap");
  .box {
    padding: 10px;
    height: 100%;
    background-color: rgb(204, 222, 238);
    border-radius: 23px;
  }
  .title-box {
    display: flex;
    text-align: center;
    justify-content: center;
    align-items: center;
  }
  .logo {
    border-radius: 23px;
  }
  .title {
    margin: 10px;
    font-family: "Cherry Bomb One", cursive;
    font-size: 70px;
    background: linear-gradient(
      132deg,
      rgba(11, 0, 108, 1) 0%,
      rgba(182, 13, 161, 1) 96%
    );
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  .download-box {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .button-1 {
    background-color: #ea4c89;
    border-radius: 8px;
    border-style: none;
    box-sizing: border-box;
    color: #ffffff;
    cursor: pointer;
    display: inline-block;
    font-family: "Haas Grot Text R Web", "Helvetica Neue", Helvetica, Arial,
      sans-serif;
    font-size: 14px;
    font-weight: 500;
    height: 40px;
    line-height: 20px;
    list-style: none;
    margin: 0;
    outline: none;
    padding: 10px 16px;
    position: relative;
    text-align: center;
    text-decoration: none;
    transition: color 100ms;
    vertical-align: baseline;
    user-select: none;
    -webkit-user-select: none;
    touch-action: manipulation;
  }

  .button-1:hover,
  .button-1:focus {
    background-color: #f082ac;
  }
</style>
