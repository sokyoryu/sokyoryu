<!doctype html>
<html dir="ltr"
      hascustombackground="false"
      lang="pt"
      class="md">
<head>
<meta charset="utf-8">
<meta name="color-scheme" content="light dark">
<title>Nova guia anônima</title>
<link rel="icon" type="image/svg+xml" href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBmaWxsPSIjNDU1QTY0Ij48cGF0aCBmaWxsPSJub25lIiBkPSJNMCAwaDI0djI0SDB6Ii8+PHBhdGggZD0iTTMgMTFoMTh2MUgzem0xNC42Mi0xLTIuMjktNi4xYy0uMTktLjUtLjc0LS43Ny0xLjI1LS42TDEyIDRsLTIuMDktLjdjLS41MS0uMTctMS4wNi4xLTEuMjUuNkw2LjM4IDEwaDExLjI0em0tMS4xMiAzYy0xLjY2IDAtMy4wNCAxLjE2LTMuNCAyLjcxLS44NC0uMzYtMS42Mi0uMjYtMi4yLS4wMUEzLjUwMyAzLjUwMyAwIDAgMCA3LjUgMTNDNS41NyAxMyA0IDE0LjU3IDQgMTYuNVM1LjU3IDIwIDcuNSAyMGMxLjg0IDAgMy4zMy0xLjQyIDMuNDctMy4yMi4zLS4yMSAxLjA5LS42IDIuMDYuMDIuMTYgMS43OSAxLjY0IDMuMiAzLjQ3IDMuMiAxLjkzIDAgMy41LTEuNTcgMy41LTMuNVMxOC40MyAxMyAxNi41IDEzem0tOSA2YTIuNSAyLjUgMCAwIDEgMC01IDIuNSAyLjUgMCAwIDEgMCA1em05IDBhMi41IDIuNSAwIDAgMSAwLTUgMi41IDIuNSAwIDAgMSAwIDV6Ii8+PC9zdmc+">
<meta name="viewport" content="width=device-width">
<link id="incognitothemecss" rel="stylesheet">
<script>
// Until themes can clear the cache, force-reload the theme stylesheet.
document.querySelector('#incognitothemecss').href =
    'chrome://theme/css/incognito_tab_theme.css?' + Date.now();
</script>
<link rel="stylesheet" href="chrome://resources/css/text_defaults_md.css">
<style>/* Copyright 2017 The Chromium Authors. All rights reserved.
 * Use of this source code is governed by a BSD-style license that can be
 * found in the LICENSE file. */

body {
  -webkit-font-smoothing: antialiased;
  font-size: 100%;
  margin: 0;
}

[hidden] {
  display: none !important;
}

/** Typography -------------------------------------------------------------- */

.content {
  color: rgb(231, 234, 237);  /* --google-grey-200 */
  font-size: calc(100% - 2px);
  line-height: calc(100% + 6px);
  min-width: 240px;
}

h1 {
  font-size: calc(100% + 8px);
  font-weight: 400;
  line-height: calc(100% + 8px);
}

em {
  color: white;
  font-style: normal;
}

.learn-more-button {
  color: rgb(138, 180, 248);
  text-decoration: none;
}

/* Small font on small screens. */
@media (max-width: 240px),
       (max-height: 320px) {
  .content {
    font-size: calc(100% - 4px);
    line-height: calc(100% + 6px);
  }

  h1 {
    font-size: calc(100% + 4px);
    line-height: calc(100% + 4px);
  }
}

/** Icon -------------------------------------------------------------------- */

.icon {
  content: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTIwIiBoZWlnaHQ9IjEyMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPjxwYXRoIGQ9Ik0wIDBoMTIwdjEyMEgweiIvPjxwYXRoIGQ9Ik02MCAwYzMzLjEzNyAwIDYwIDI2Ljg2MyA2MCA2MHMtMjYuODYzIDYwLTYwIDYwUzAgOTMuMTM3IDAgNjAgMjYuODYzIDAgNjAgMHptMTcuNSA2NC44MzdjLTYuNDU2IDAtMTEuODIyIDQuNTAyLTEzLjIyMiAxMC41MTYtMy4yNjctMS4zOTctNi4zLTEuMDA5LTguNTU2LS4wMzlDNTQuMjgzIDY5LjMgNDguOTE3IDY0LjgzNyA0Mi41IDY0LjgzN2MtNy41MDYgMC0xMy42MTEgNi4wOTItMTMuNjExIDEzLjU4MkMyOC44ODkgODUuOTA4IDM0Ljk5NCA5MiA0Mi41IDkyYzcuMTU2IDAgMTIuOTUtNS41MSAxMy40OTQtMTIuNDk1IDEuMTY3LS44MTUgNC4yNC0yLjMyOCA4LjAxMi4wNzhDNjQuNjI4IDg2LjUyOSA3MC4zODMgOTIgNzcuNSA5MmM3LjUwNiAwIDEzLjYxMS02LjA5MiAxMy42MTEtMTMuNTgxIDAtNy40OS02LjEwNS0xMy41ODItMTMuNjExLTEzLjU4MnptLTM1IDMuODhjNS4zNjcgMCA5LjcyMiA0LjM0NyA5LjcyMiA5LjcwMiAwIDUuMzU1LTQuMzU1IDkuNy05LjcyMiA5LjctNS4zNjcgMC05LjcyMi00LjM0NS05LjcyMi05LjcgMC01LjM1NSA0LjM1NS05LjcwMSA5LjcyMi05LjcwMXptMzUgMGM1LjM2NyAwIDkuNzIyIDQuMzQ3IDkuNzIyIDkuNzAyIDAgNS4zNTUtNC4zNTUgOS43LTkuNzIyIDkuNy01LjM2NyAwLTkuNzIyLTQuMzQ1LTkuNzIyLTkuNyAwLTUuMzU1IDQuMzU1LTkuNzAxIDkuNzIyLTkuNzAxek05NSA1N0gyNXY0aDcwdi00ek03Mi44NzQgMjkuMzRjLS44LTEuODItMi44NjYtMi43OC00Ljc4NS0yLjE0M0w2MCAyOS45MTRsLTguMTI4LTIuNzE3LS4xOTItLjA1OGMtMS45MjgtLjUzMy0zLjk1NC41MS00LjY2OSAyLjM4N0wzOC4xNDQgNTNoNDMuNzEyTDcyLjk1IDI5LjUyNnoiIGZpbGw9IiNEQURDRTAiLz48L2c+PC9zdmc+);
  height: 120px;
  width: 120px;
}

/* Medium-sized icon on medium-sized screens. */
@media (max-height: 480px),
       (max-width: 720px) {
  .icon {
    height: 72px;
    width: 72px;
  }
}

/* Very small icon on very small screens. */
@media (max-width: 720px) {
  @media (max-width: 240px),
         (max-height: 480px) {
    .icon {
      height: 48px;
      width: 48px;
    }
  }
}

/** The "Learn more" link --------------------------------------------------- */

/* By default, we only show the inline "Learn more" link. */
.content > .learn-more-button {
  display: none;
}

/* On narrow screens, we show the standalone "Learn more" link. */
@media (max-width: 720px) {
  #subtitle > .learn-more-button {
    display: none;
  }

  .content > .learn-more-button {
    display: block;
  }
}

/** Cookie Controls --------------------------------------------------------- */

#cookie-controls {
  align-items: center;
  background-color: rgb(60, 64, 67); /* --google-grey-800 */
  border-radius: 4px;
  box-sizing: border-box;
  display: flex;
  padding: 12px 20px;
}

#cookie-controls-description {
  flex: 1;
  padding-inline-end: 12px;
}

#cookie-controls-description em {
  display: block;
}

#cookie-controls-toggle,
#cookie-controls-tooltip-icon {
  flex: none;
}

#cookie-controls-toggle:not(:defined) {
  width: 34px;
}

#cookie-controls-tooltip-icon {
  margin-inline-end: 24px; /* var(--cr-controlled-by-spacing) */
}

#cookie-controls-tooltip-icon:not(:defined) {
  width: 20px; /* var(--cr-icon-size) */
}

/** Layout ------------------------------------------------------------------ */

/* Align the content, icon, and title to to the center. */
.content {
  margin-inline-end: auto;
  margin-inline-start: auto;
  max-width: 600px;
}

.icon {
  margin-inline-end: auto;
  margin-inline-start: auto;
}

h1 {
  text-align: center;
}

/* Align the two columns of bulletpoints next to each other. */
#bulletpoints-wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.bulletpoints {
  flex-basis: 285px;  /* (600px - 30px) / 2. */
  flex-grow: 1;
  flex-shrink: 0;
}

.bulletpoints.first {
  margin-inline-end: 30px;
}

/* On narrow screens, align everything to the left. */
@media (max-width: 720px) {
  .content {
    max-width: 600px !important;  /* must override the rule set by JS which
                                   * is only valid for width > 720px cases. */
    text-align: start;
  }

  .icon {
    margin-inline-start: 0;
  }

  h1 {
    text-align: start;
  }
}

/** Paddings and margins ---------------------------------------------------- */

.bulletpoints ul {
  margin: 4px 0 0;
  padding-inline-start: 16px;
}

/* Wide screens. */
@media (min-width: 720px) {
  .icon,
  h1,
  #subtitle,
  .learn-more-button {
    margin-top: 1.5rem;
  }

  .icon,
  h1,
  #subtitle,
  .bulletpoints,
  #cookie-controls {
    margin-bottom: 1.5rem;
  }

  .content {
    margin-top: 40px;
    min-width: 240px;
    padding: 8px 48px 24px;
  }

  /* Snap the content box to the whole height on short screens. */
  @media (max-height: 480px) {
    html,
    body,
    .content {
      height: 100%;
    }

    .content {
      margin-bottom: 0;
      margin-top: 0;
      padding-bottom: 0;
      padding-top: 0;
    }

    .icon {
      margin-top: 0;
      padding-top: 32px;  /* Define the top offset through the icon's padding,
                           * otherwise the screen height would be 100% + 32px */
    }
  }

  /* Smaller vertical margins on very short screens. */
  @media (max-height: 320px) {
    h1,
    #subtitle {
      margin-bottom: 16px;
      margin-top: 16px;
    }

    .learn-more-button,
    .bulletpoints,
    .icon,
    #cookie-controls {
      margin-bottom: 16px;
    }
  }
}

/* Narrow screens */
@media (max-width: 720px) {
  .content {
    min-width: 176px;
    padding: 72px 32px;
  }

  .icon,
  h1,
  #subtitle {
    margin-bottom: 1.5rem;
    margin-top: 1.5rem;
  }

  .bulletpoints,
  .learn-more-button,
  #cookie-controls {
    margin-bottom: 1.5rem;
  }

  /* Smaller offsets on smaller screens. */
  @media (max-height: 600px) {
    .content {
      padding-top: 48px;
    }

    .icon,
    h1,
    #subtitle {
      margin-bottom: 1rem;
      margin-top: 1rem;
    }

    .bulletpoints,
    .learn-more-button,
    #cookie-controls {
      margin-bottom: 1rem;
    }
  }

  /* Small top offset on very small screens. */
  @media (max-height: 480px) {
    .content {
      padding-top: 31px;
    }
  }

  /* Undo the first and last elements margins. */
  .icon {
    margin-top: 0;
  }

  .learn-more-button {
    margin-bottom: 0;
  }
}

/* Very narrow screens. */
@media (max-width: 240px) {
  .content {
    min-width: 192px;
    padding-inline-end: 24px;
    padding-inline-start: 24px;
  }
}
</style>
</head>
<body>
<div class="content">
  <div class="icon" role="presentation" alt=""></div>
  <h1>Você entrou no modo de navegação anônima</h1>
  <p id="subtitle">
    <span>Agora você pode navegar com privacidade, e as outras pessoas que usarem este dispositivo não verão suas atividades. No entanto, os downloads, favoritos e itens da Lista de leitura ainda serão salvos.</span>
    <a class="learn-more-button"
        href="https://support.google.com/chrome/?p=incognito">Saiba mais</a>
  </p>
  <div id="bulletpoints-wrapper">
    <div class="bulletpoints first">O Chrome <em>não vai salvar</em> estas informações:
          <ul>
            <li>Seu histórico de navegação
            <li>Cookies e dados de sites
            <li>Informações inseridas em formulários
          </ul></div>
    <div class="bulletpoints">É possível que sua atividade <em>ainda esteja visível</em> para:
        <ul>
          <li>os websites que você visita
          <li>seu empregador ou sua escola
          <li>seu provedor de acesso à Internet
        </ul></div>
  </div>
  <div id="cookie-controls">
    <div id="cookie-controls-description">
      <em>Bloquear cookies de terceiros</em>
      Com esse recurso ativado, os sites não podem usar cookies que rastreiem você pela Internet. Algumas funções dos sites podem não funcionar.
    </div>
    <cr-tooltip-icon id="cookie-controls-tooltip-icon"
        icon-aria-label="Bloquear cookies de terceiros"
        icon-class=""
        tooltip-text="Essa configuração é controlada nas configurações de cookies."
        role="link" style="cursor: pointer;" hidden>
    </cr-tooltip-icon>
    <cr-toggle id="cookie-controls-toggle"
               aria-label="Bloquear cookies de terceiros"
               checked dark></cr-toggle>
  </div>
  <a class="learn-more-button" href="https://support.google.com/chrome/?p=incognito">Saiba mais</a>
</div>
<script type="module">// Copyright 2017 The Chromium Authors. All rights reserved.
// Use of this source code is governed by a BSD-style license that can be
// found in the LICENSE file.

import {addWebUIListener} from 'chrome://resources/js/cr.m.js';
import {$} from 'chrome://resources/js/util.m.js';

window.addEventListener('load', function() {
  let cookieSettingsUrl;

  addWebUIListener('theme-changed', themeData => {
    document.documentElement.setAttribute(
        'hascustombackground', themeData.hasCustomBackground);
    $('incognitothemecss').href =
        'chrome://theme/css/incognito_tab_theme.css?' + Date.now();
  });
  chrome.send('observeThemeChanges');

  addWebUIListener('cookie-controls-changed', dict => {
    $('cookie-controls-tooltip-icon').hidden = !dict.enforced;
    $('cookie-controls-tooltip-icon').iconClass = dict.icon;
    $('cookie-controls-toggle').disabled = dict.enforced;
    $('cookie-controls-toggle').checked = dict.checked;
    cookieSettingsUrl = dict.cookieSettingsUrl;
  });
  $('cookie-controls-toggle').addEventListener('change', event => {
    chrome.send('cookieControlsToggleChanged', [event.detail]);
  });
  // Make cookie-controls-tooltip-icon respond to the enter key.
  $('cookie-controls-tooltip-icon').addEventListener('keyup', event => {
    if (event.key === 'Enter') {
      $('cookie-controls-tooltip-icon').click();
    }
  });
  $('cookie-controls-tooltip-icon').onclick = () => {
    window.location.href = cookieSettingsUrl;
  };
  chrome.send('observeCookieControlsSettingsChanges');
});
</script>
<!-- Lazy-load cr_elements to avoid performance penalty introduced by loading Polymer -->
<script type="module" src="chrome://resources/cr_elements/cr_toggle/cr_toggle.m.js" async></script>
<script type="module" src="chrome://resources/cr_elements/policy/cr_tooltip_icon.m.js" async></script>
</body>
</html>
