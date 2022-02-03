<div class="Share">
    <div class="share-header">
        <h2>Compartir</h2>
        <i class="fas fa-times-circle" on:click />
    </div>
    <div class="share-content">
        <a href="https://www.facebook.com/sharer/sharer.php?&u=https://catstagram.co/"  target="_blank">
            <i class="fab fa-facebook-square"/> 
            Compartir en Facebook
        </a>
        <a href="https://api.whatsapp.com/send?&text=Checa%20este%20gato%20https://pugstagram.co/" target="_blank">
            <i class="fab fa-whatsapp-square" />
            Compartir en Whatsapp!
        </a>          
    </div>
</div>

<style>
    .Share {
      border: 1px solid rgba(219, 219, 219, 1);
      border-radius: 4px;
      background-color: white;
      width: 300px;
      height: fit-content;
      position: absolute;
      top: 300px;
      left: 30%;
      z-index: 9;
      padding: 1em;
    }
    .share-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .share-header h2 {
      font-size: 16px;
    }
    .share-header i {
      cursor: pointer;
    }
    .share-content a {
      display: flex;
      align-items: center;
      text-decoration: none;
      color: black;
      font-size: 14px;
      margin: 2em 0 0 0;
    }
    .share-content i {
      color: #3b5998;
      margin: 0 0.5em 0 0;
      font-size: 20px;
    }
</style>