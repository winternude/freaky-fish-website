<div class="main-container">
    <div class="text-container">
        <p class="headline text-xl green-text">This is a placeholder</p>
        <p class="copy text-sm green-text">Artist works with words, sounds, and other living media. There are audiovisual pieces, sculptures, and performances seek to identify and react to precarious social and material moments, often in relation to technology. The work has been presented.</p>
    </div>
    <div class="container">
        <div class="grid">
                <div class="item red">
                        <img class="image" src="$static/assets/frame-export-2.jpg" alt="alt text">
                </div>
                <div class="item green">
                        <img class="image" src="./src/assets/frame-export-1.jpg" alt="alt text">
                </div>
                <div class="item red">
                        <img class="image" src="./src/assets/frame-export-3.jpg" alt="alt text">
                </div>
                <div class="item green">
                        <img class="image" src="./src/assets/frame-export-1.jpg" alt="alt text">
                </div>
                <div class="item green">
                        <img class="image" src="./src/assets/frame-export-4.jpg" alt="alt text">
                </div>
                <div class="item green">
                        <img class="image" src="./src/assets/frame-export-3.jpg" alt="alt text">
                </div>
        </div>
    </div>
</div>

<style>
    .main-container {
        width: 100vw;
        padding: 60px 0 0 0;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background: radial-gradient(50% 50% at 50% 50%, #05FF00 40.02%, #000000 100%);
        mix-blend-mode: normal;
    }

    .container {
        background-color: black;
        display: flex;
        justify-content: center;
    }
    .grid {
        display: inline-grid;
        justify-content: stretch;
        gap: 0px;
        width: 100%;
        grid-template-columns: auto auto auto;

    }

    .item {
        height: 60vh;
        width: 100%;
        justify-self: auto;
    }

    .text-container {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 16px;
        width: 600px;
        text-align: center;
        margin: 4em;
    }

    h1 {
        font-size: 28px;
    }

    .image {
        height: 100%;
    }

    .red {
        background-color: red
    }

    .green {
        background-color: green;
    }
</style>