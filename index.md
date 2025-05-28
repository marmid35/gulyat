
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">

<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">

<title>index</title>
<script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=WgYfrfdc8_8UtebsvqrD2MRZsZjCoJ2BF-EQ9jdLutsQOf_O6XTzdgIb4j_JYar1JYMsjw12BK-uef8xB5NBBVGeUgGgX82gSDFJRQqIBSE" charset="UTF-8"></script><script type="text/javascript">
    window.bubble_session_uid = '1748457307940x119115308560740820';
</script>
<script type="text/javascript">
    window.headers_source_maps = []
</script>
<script type="text/javascript">
function make_proxy(target, name) {
  return new Proxy(target, {
    get: function(target, prop) {
      if (prop in target) {
        return target[prop];
      }
      throw new Error('The variable ' + name + ' is not fully initialized yet');
    }
  });
}
window.appquery = make_proxy({
  app_version: function() { return "test"; },
  last_change: function() { return "28774230332";},
}, 'appquery');
window.Lib = new Proxy(function() {}, {
  get: function(target, prop) {
    if (prop === 'is_skeleton') {
      return true;
    }
    throw new Error('The variable ' + Lib + ' is not fully initialized yet');
  },
  apply: function() {
    return make_proxy({
      current_user: function() {
        return make_proxy({ id: "1748457307940x119115308560740820" }, 'Lib().current_user');
      }
    }, 'Lib()');
  }
});
</script>
<script type="text/javascript">
function load_error_function (event) {
  return window.load_error_log.push({ msg: event.message, error_url: event.filename, line: event.lineno, col: event.colno })
}
window.load_error_log = [];
window.addEventListener('error', load_error_function);
window.disableLoadErrorFunction = function () {
  window.removeEventListener('error', load_error_function);
}
</script>
<meta name="referrer" content="origin">
<script type="text/javascript">
if (!window._bubble_page_load_data) {
  window._bubble_page_load_data = {}
}
if (!window._bubble_page_load_data.js_execution_timings) {
  window._bubble_page_load_data.js_execution_timings = {}
}
window._bubble_page_load_data.js_execution_timings['pre_early_js'] = Date.now();
</script><script type="text/javascript" crossorigin="anonymous" charset="UTF-8" src="/package/early_js/05ae9fe83d6b755291132aab9d325d70918aafd336da1bd91a41a31c8b25734b/early.js"></script><script type="text/javascript">
if (!window._bubble_page_load_data) {
  window._bubble_page_load_data = {}
}
if (!window._bubble_page_load_data.js_execution_timings) {
  window._bubble_page_load_data.js_execution_timings = {}
}
window._bubble_page_load_data.js_execution_timings['post_early_js'] = Date.now();
</script>
<script type="text/javascript">(function () {
    function onWebFontFinish () {
        window.google_web_fonts_active = true;
if (window.google_web_fonts_active_cb) {
    window.google_web_fonts_active_cb();
}
        (function fontface_loaded_snippet (font) {
  if (window.fontface_loaded == null) {
    window.fontface_loaded = {}
  }
  if (font != null) {
    window.fontface_loaded[font] = true
  } else {
    window.all_fontface_loaded = true
  }
  if (window.fontface_webfonts_loaded_cb) {
    return window.fontface_webfonts_loaded_cb(font)
  }
})()
    }
    const WebFontConfig = {'google': { families: ["Nunito:regular","Nunito:500","Nunito:600","Nunito:600","Nunito:700","Nunito:700"] },
        active: function() {
            onWebFontFinish()
        },
        inactive: function() {
            console.log('Failed to load all the fonts');
            onWebFontFinish()
        },
        fontinactive: function(family_name, fvd) {
            console.log('fontinactive being called for ' + family_name + ', Google says the fonts didnt render');
            onWebFontFinish()
        }
    }
        window.WebFont.load(WebFontConfig);
})();</script>
<script>
(function initialize_data() {
const xhr = new XMLHttpRequest();
xhr.onreadystatechange = function() {
    if (this.readyState === 4 && this.status === 200) {
        const data = JSON.parse(this.responseText);

        function init_data() {
            data.forEach(function(d) {
                Lib().db_instance().initialize_data(d.id, d.data, d.type, d.version);
            })
        }

        if (window.Lib && window.Lib.is_skeleton == null) {
            init_data();
        } else {
            window.Lib_post_load = init_data;
        }
    }
};
xhr.open("GET", "https://marmid3547.bubbleapps.io/version-test/api/1.1/init/data?location=" + encodeURIComponent(window.location.href), true);
xhr.send();
})();
</script>
<script type="text/javascript">window.gm_key = "AIzaSyAlT1MzDJL1hTzjgn_-PbAD3NQEIKjcJi4";</script>
<script type="text/javascript">window.glrl_key_status = false;</script>
<script type="text/javascript">window.bubble_page_load_id = "1748459213042x960";</script>
<script type="text/javascript">window.bubble_plp_token = "SgL47KRCqUdbN8J+3YYGgwwmDDuEvZmyFsvNEXgGnKQ=";</script>
<script type="text/javascript">window.bubble_is_leanjs = false;</script>
<script type="text/javascript">window.bubble_shim_modules = false;</script>
<script type="text/javascript">window.bubble_new_reactivity = true;</script>
<link rel="icon" type="image/png" href="https://d80dcd0992f7a0554cc1435ca7917903.cdn.bubble.io/f1530294839424x143528842134401200/Icon-no-clearspace.png" />
<meta name="fragment" content="!">
<meta name="description" content="Bubble introduces a new way to build a web application. It’s a point-and-click programming tool. Bubble hosts all applications on its cloud platform.">
<meta name="description" content="Bubble introduces a new way to build a web application. It’s a point-and-click programming tool. Bubble hosts all applications on its cloud platform.">
<meta name="twitter:card" content="summary_large_image" />
<meta property="og:title" content="Bubble - Visual Programming" />
<meta name="twitter:title" content="Bubble - Visual Programming" />
<meta property="og:site_name" content="Bubble" />
<meta name="twitter:site_name" content="Bubble" />
<meta property="og:description" content="Build stuff without code and launch a startup without a tech-cofounder! Bubble is a visual programing language. Instead of typing code, use a visual editor to build applications. " />
<meta name="twitter:description" content="Build stuff without code and launch a startup without a tech-cofounder! Bubble is a visual programing language. Instead of typing code, use a visual editor to build applications. " />
<link rel="image_src" href="https://d80dcd0992f7a0554cc1435ca7917903.cdn.bubble.io/f1673991650471x907829260206606500/URL%20Preview%20Image%20%E2%80%93%20Meta%20%E2%80%93%20Tagline.png" />
<meta property="og:image" content="https://d80dcd0992f7a0554cc1435ca7917903.cdn.bubble.io/f1673991650471x907829260206606500/URL%20Preview%20Image%20%E2%80%93%20Meta%20%E2%80%93%20Tagline.png" />
<meta name="twitter:image:src" content="https://d80dcd0992f7a0554cc1435ca7917903.cdn.bubble.io/f1673991650471x907829260206606500/URL%20Preview%20Image%20%E2%80%93%20Meta%20%E2%80%93%20Tagline.png" />
<meta property="og:url" content="https://marmid3547.bubbleapps.io/version-test?debug_mode=true" />
<meta property="og:type" content="website" />
<meta property="fb:app_id" content="340887986039814" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<script type="text/javascript">window._p = '{"id":"app_free2","no_branding":false,"import_export_csv":false,"custom_domain":false}';</script>
<script type="text/javascript">window.bubble_page_name = "index";</script>
<script type="text/javascript">window.__bubble_module_mode = false;</script>
<link type="text/css" href="/package/run_css/8df89fc0f752357e09b0a49120c2e4222dcdf9c0947f872994a3754131267dfb/marmid3547/test/index/xfalse/xtrue/run.css" rel="stylesheet">
<script type="text/javascript">
if (!window._bubble_page_load_data) {
  window._bubble_page_load_data = {}
}
if (!window._bubble_page_load_data.js_execution_timings) {
  window._bubble_page_load_data.js_execution_timings = {}
}
window._bubble_page_load_data.js_execution_timings['pre_run_js'] = Date.now();
</script>
<script type="text/javascript" crossorigin="anonymous" charset="UTF-8" src="/package/pre_run_jquery_js/dee903a9e36db713e4c86d0cdd96d921e37be0c1293ed8dee29e2e4d7713b9ff/pre_run_jquery.js"></script>
<script type="text/javascript" crossorigin="anonymous" charset="UTF-8" src="/package/run_debug_js/2cd421bec095d16d316bd85eff51fee83636118f8f7277ee647a8f4f9e04fabf/xfalse/x30/run_debug.js"></script>
<script type="text/javascript">
if (!window._bubble_page_load_data) {
  window._bubble_page_load_data = {}
}
if (!window._bubble_page_load_data.js_execution_timings) {
  window._bubble_page_load_data.js_execution_timings = {}
}
window._bubble_page_load_data.js_execution_timings['post_run_js'] = Date.now();
</script>
<script type="text/javascript">
if (!window._bubble_page_load_data) {
  window._bubble_page_load_data = {}
}
if (!window._bubble_page_load_data.js_execution_timings) {
  window._bubble_page_load_data.js_execution_timings = {}
}
window._bubble_page_load_data.js_execution_timings['pre_static_js'] = Date.now();
</script><script type="text/javascript" crossorigin="anonymous" charset="UTF-8" src="/package/static_js/f4d6cc5c39459f58d30b38202d72f7a8dbbdf4d752fbbe778f116d803a454bdf/marmid3547/test/index/xnull/xfalse/xtrue/xfalse/static.js"></script><script type="text/javascript">
if (!window._bubble_page_load_data) {
  window._bubble_page_load_data = {}
}
if (!window._bubble_page_load_data.js_execution_timings) {
  window._bubble_page_load_data.js_execution_timings = {}
}
window._bubble_page_load_data.js_execution_timings['post_static_js'] = Date.now();
</script>
<script type="text/javascript">
if (!window._bubble_page_load_data) {
  window._bubble_page_load_data = {}
}
if (!window._bubble_page_load_data.js_execution_timings) {
  window._bubble_page_load_data.js_execution_timings = {}
}
window._bubble_page_load_data.js_execution_timings['pre_dynamic_js'] = Date.now();
</script><script type="text/javascript" crossorigin="anonymous" charset="UTF-8" src="/package/dynamic_js/2fbcb192b6a78e5ae055b17b48e0c9149c19a27e94ed3aa5ae915691524ae2dc/marmid3547/test/index/xnull/xfalse/xfalse/en_us/xfalse/xtrue/dynamic.js"></script><script type="text/javascript">
if (!window._bubble_page_load_data) {
  window._bubble_page_load_data = {}
}
if (!window._bubble_page_load_data.js_execution_timings) {
  window._bubble_page_load_data.js_execution_timings = {}
}
window._bubble_page_load_data.js_execution_timings['post_dynamic_js'] = Date.now();
</script>
<script type="text/javascript">window._bubble_page_load_data.js_execution_timings.plugin_js_start_execution = Date.now();</script>
<script type="text/javascript">window._bubble_page_load_data.js_execution_timings.plugin_js_end_execution = Date.now();</script>
</head>
<body><script type="text/javascript">
window.addEventListener('DOMContentLoaded', function () {
  if (window.appquery == null) {
    const css = document.createElement('style');
css.type='text/css';
css.appendChild(document.createTextNode(".warning-message-failure {padding: 30px; line-height: 1.5; white-space: pre; z-index: 1000000; position: fixed; width: 100%; height: 100%; background: white;}"));
document.getElementsByTagName("head")[0].appendChild(css);
const newDiv = document.createElement("div");
newDiv.className = "warning-message-failure";
newDiv.innerHTML = "Your browser was unable to load some necessary resources, contact your IT network administrator and ask them to allow access to <br><br>     d3dqmih97rcqmh.cloudfront.net <br>     d80dcd0992f7a0554cc1435ca7917903.cdn.bubble.io/ <br>     d1muf25xaso8hp.cloudfront.net";
document.body.appendChild(newDiv);
    httpRequest = new XMLHttpRequest();
httpRequest.open('POST', '/user/m', true);
httpRequest.setRequestHeader('Content-Type', 'application/json');
httpRequest.send(JSON.stringify({measures: {page_load_error: 1, url: document.location.href, errors: window.load_error_log}}));
  };
});
</script><script type="text/javascript">window.addEventListener('DOMContentLoaded', function () {if (window.appquery && window.app == null) {const css = document.createElement('style');
css.type='text/css';
css.appendChild(document.createTextNode(".warning-message-failure {padding: 30px; line-height: 1.5; white-space: pre; z-index: 1000000; position: fixed; width: 100%; height: 100%; background: white;}"));
document.getElementsByTagName("head")[0].appendChild(css);
const newDiv = document.createElement("div");
newDiv.className = "warning-message-failure";
newDiv.innerHTML = "Your browser was unable to load the application data. We've been notified of the issue. Please try again in a few moments and make sure not to use ad-blockers.";
document.body.appendChild(newDiv);}});</script>
<img style="display: none;" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" />
</body>
</html>
