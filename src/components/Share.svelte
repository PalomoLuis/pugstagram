<div class="share">
    <div class="share-head">
        <h2>Compartir</h2>
        <button class="close" on:click >
          <i class="fas fa-times-circle" />
        </button>
    </div>
    <div class="share-content">
        <a href="https://www.facebook.com/sharer/sharer.php?&u=https://pugstagram.co"
          target="_blank"
          rel="noopener noreferrer">
            <i class="fab fab-facebook-square" />
            Compartir en facebook
        </a>
    </div>
</div>

<style>
    .share {
      border: 1px solid rgba(219, 219, 219, 1);
      border-radius: 4px;
      background-color: white;
      margin: 0 0 2em 0;
      width: 300px;
      height: 80px;
      position: absolute;
      top: 300px;
      left: 30%;
      z-index: 9;
      padding: 1em;
    }
    .share-head {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .share-head h2 {
      font-size: 16px;
    }
    .share-head i {
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

    .close {
      padding: 0;
      margin: 0;
      background: none;
      border: none;
      color: unset;
    }
</style>