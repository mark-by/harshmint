<div class="wrapper">
    <div class="main-info">
        <p class="main-info__logo">HARSHMINT</p>
        <p class="main-info__text">делаем проекты</p>
    </div>

    <div class="contact-info">
        <p><span class="hint">почта:</span> <a href="mailto:order@harshmint.ru">order@harshmint.ru</a> <span class="hint">telegram:</span> <a target="_blank" href="https://t.me/mark_by">@mark_by</a></p>
    </div>
</div>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue', sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
    }

    a, a:hover, a:focus, a:active {
        text-decoration: none;
        color: inherit;
    }

    .wrapper {
        position: absolute;
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
        background: radial-gradient(50% 50% at 50% 50%, #3989c2 0%, #3340B9 100%);
    }

    .main-info {
        position: absolute;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    .main-info__logo {
        font-style: normal;
        font-weight: 700;
        font-size: 120px;
        color: rgba(255, 255, 255, 0.7);
        text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    }

    .main-info__text {
        font-style: normal;
        font-weight: 700;
        font-size: 50px;
        color: rgba(0, 0, 0, 0.1);
    }

    .contact-info {
        position: absolute;
        width: 100%;
        text-align: center;
        left: 50%;
        bottom: 20px;
        transform: translate(-50%, 0);
        font-style: normal;
        font-weight: 400;
        font-size: 32px;

        color: rgba(0, 0, 0, 0.3);
    }

    .hint {
        color: rgba(0, 0, 0, 0.1);
    }

    @media screen and (max-width: 500px) {
        .main-info__logo {
            font-size: 40px;
        }

        .main-info__text {
            font-size: 24px;
        }

        .contact-info {
            font-size: 16px;
        }
    }
</style>