- 👋 Hi, I’m @AkhileshMalviyaSystango
<!doctype html>
<!--[if IE 7]><html class="ie ie7"><![endif]-->
<!--[if IE 8]><html class="ie ie8"><![endif]-->
<!--[if !(IE 7) | !(IE 8)]><!-->
<html>
<!--<![endif]-->

    <head>
                <title>  Tickets
 | Picoworkers</title>
        <meta charset="utf-8"><script type="text/javascript">(window.NREUM||(NREUM={})).init={privacy:{cookies_enabled:true},ajax:{deny_list:["bam.nr-data.net"]},distributed_tracing:{enabled:true}};(window.NREUM||(NREUM={})).loader_config={agentID:"875177040",accountID:"2632909",trustKey:"2632909",xpid:"VgAEU19TARAIU1RTAAcEX1M=",licenseKey:"NRJS-5227eab768865ec54b6",applicationID:"875176397"};window.NREUM||(NREUM={}),__nr_require=function(t,e,n){function r(n){if(!e[n]){var o=e[n]={exports:{}};t[n][0].call(o.exports,function(e){var o=t[n][1][e];return r(o||e)},o,o.exports)}return e[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var o=0;o<n.length;o++)r(n[o]);return r}({1:[function(t,e,n){function r(t){try{s.console&&console.log(t)}catch(e){}}var o,i=t("ee"),a=t(31),s={};try{o=localStorage.getItem("__nr_flags").split(","),console&&"function"==typeof console.log&&(s.console=!0,o.indexOf("dev")!==-1&&(s.dev=!0),o.indexOf("nr_dev")!==-1&&(s.nrDev=!0))}catch(c){}s.nrDev&&i.on("internal-error",function(t){r(t.stack)}),s.dev&&i.on("fn-err",function(t,e,n){r(n.stack)}),s.dev&&(r("NR AGENT IN DEVELOPMENT MODE"),r("flags: "+a(s,function(t,e){return t}).join(", ")))},{}],2:[function(t,e,n){function r(t,e,n,r,s){try{l?l-=1:o(s||new UncaughtException(t,e,n),!0)}catch(f){try{i("ierr",[f,c.now(),!0])}catch(d){}}return"function"==typeof u&&u.apply(this,a(arguments))}function UncaughtException(t,e,n){this.message=t||"Uncaught error with no additional information",this.sourceURL=e,this.line=n}function o(t,e){var n=e?null:c.now();i("err",[t,n])}var i=t("handle"),a=t(32),s=t("ee"),c=t("loader"),f=t("gos"),u=window.onerror,d=!1,p="nr@seenError";if(!c.disabled){var l=0;c.features.err=!0,t(1),window.onerror=r;try{throw new Error}catch(h){"stack"in h&&(t(14),t(13),"addEventListener"in window&&t(7),c.xhrWrappable&&t(15),d=!0)}s.on("fn-start",function(t,e,n){d&&(l+=1)}),s.on("fn-err",function(t,e,n){d&&!n[p]&&(f(n,p,function(){return!0}),this.thrown=!0,o(n))}),s.on("fn-end",function(){d&&!this.thrown&&l>0&&(l-=1)}),s.on("internal-error",function(t){i("ierr",[t,c.now(),!0])})}},{}],3:[function(t,e,n){var r=t("loader");r.disabled||(r.features.ins=!0)},{}],4:[function(t,e,n){function r(){U++,L=g.hash,this[u]=y.now()}function o(){U--,g.hash!==L&&i(0,!0);var t=y.now();this[h]=~~this[h]+t-this[u],this[d]=t}function i(t,e){E.emit("newURL",[""+g,e])}function a(t,e){t.on(e,function(){this[e]=y.now()})}var s="-start",c="-end",f="-body",u="fn"+s,d="fn"+c,p="cb"+s,l="cb"+c,h="jsTime",m="fetch",v="addEventListener",w=window,g=w.location,y=t("loader");if(w[v]&&y.xhrWrappable&&!y.disabled){var x=t(11),b=t(12),E=t(9),R=t(7),O=t(14),T=t(8),S=t(15),P=t(10),M=t("ee"),C=M.get("tracer"),N=t(23);t(17),y.features.spa=!0;var L,U=0;M.on(u,r),b.on(p,r),P.on(p,r),M.on(d,o),b.on(l,o),P.on(l,o),M.buffer([u,d,"xhr-resolved"]),R.buffer([u]),O.buffer(["setTimeout"+c,"clearTimeout"+s,u]),S.buffer([u,"new-xhr","send-xhr"+s]),T.buffer([m+s,m+"-done",m+f+s,m+f+c]),E.buffer(["newURL"]),x.buffer([u]),b.buffer(["propagate",p,l,"executor-err","resolve"+s]),C.buffer([u,"no-"+u]),P.buffer(["new-jsonp","cb-start","jsonp-error","jsonp-end"]),a(T,m+s),a(T,m+"-done"),a(P,"new-jsonp"),a(P,"jsonp-end"),a(P,"cb-start"),E.on("pushState-end",i),E.on("replaceState-end",i),w[v]("hashchange",i,N(!0)),w[v]("load",i,N(!0)),w[v]("popstate",function(){i(0,U>1)},N(!0))}},{}],5:[function(t,e,n){function r(){var t=new PerformanceObserver(function(t,e){var n=t.getEntries();s(v,[n])});try{t.observe({entryTypes:["resource"]})}catch(e){}}function o(t){if(s(v,[window.performance.getEntriesByType(w)]),window.performance["c"+p])try{window.performance[h](m,o,!1)}catch(t){}else try{window.performance[h]("webkit"+m,o,!1)}catch(t){}}function i(t){}if(window.performance&&window.performance.timing&&window.performance.getEntriesByType){var a=t("ee"),s=t("handle"),c=t(14),f=t(13),u=t(6),d=t(23),p="learResourceTimings",l="addEventListener",h="removeEventListener",m="resourcetimingbufferfull",v="bstResource",w="resource",g="-start",y="-end",x="fn"+g,b="fn"+y,E="bstTimer",R="pushState",O=t("loader");if(!O.disabled){O.features.stn=!0,t(9),"addEventListener"in window&&t(7);var T=NREUM.o.EV;a.on(x,function(t,e){var n=t[0];n instanceof T&&(this.bstStart=O.now())}),a.on(b,function(t,e){var n=t[0];n instanceof T&&s("bst",[n,e,this.bstStart,O.now()])}),c.on(x,function(t,e,n){this.bstStart=O.now(),this.bstType=n}),c.on(b,function(t,e){s(E,[e,this.bstStart,O.now(),this.bstType])}),f.on(x,function(){this.bstStart=O.now()}),f.on(b,function(t,e){s(E,[e,this.bstStart,O.now(),"requestAnimationFrame"])}),a.on(R+g,function(t){this.time=O.now(),this.startPath=location.pathname+location.hash}),a.on(R+y,function(t){s("bstHist",[location.pathname+location.hash,this.startPath,this.time])}),u()?(s(v,[window.performance.getEntriesByType("resource")]),r()):l in window.performance&&(window.performance["c"+p]?window.performance[l](m,o,d(!1)):window.performance[l]("webkit"+m,o,d(!1))),document[l]("scroll",i,d(!1)),document[l]("keypress",i,d(!1)),document[l]("click",i,d(!1))}}},{}],6:[function(t,e,n){e.exports=function(){return"PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver}},{}],7:[function(t,e,n){function r(t){for(var e=t;e&&!e.hasOwnProperty(u);)e=Object.getPrototypeOf(e);e&&o(e)}function o(t){s.inPlace(t,[u,d],"-",i)}function i(t,e){return t[1]}var a=t("ee").get("events"),s=t("wrap-function")(a,!0),c=t("gos"),f=XMLHttpRequest,u="addEventListener",d="removeEventListener";e.exports=a,"getPrototypeOf"in Object?(r(document),r(window),r(f.prototype)):f.prototype.hasOwnProperty(u)&&(o(window),o(f.prototype)),a.on(u+"-start",function(t,e){var n=t[1];if(null!==n&&("function"==typeof n||"object"==typeof n)){var r=c(n,"nr@wrapped",function(){function t(){if("function"==typeof n.handleEvent)return n.handleEvent.apply(n,arguments)}var e={object:t,"function":n}[typeof n];return e?s(e,"fn-",null,e.name||"anonymous"):n});this.wrapped=t[1]=r}}),a.on(d+"-start",function(t){t[1]=this.wrapped||t[1]})},{}],8:[function(t,e,n){function r(t,e,n){var r=t[e];"function"==typeof r&&(t[e]=function(){var t=i(arguments),e={};o.emit(n+"before-start",[t],e);var a;e[m]&&e[m].dt&&(a=e[m].dt);var s=r.apply(this,t);return o.emit(n+"start",[t,a],s),s.then(function(t){return o.emit(n+"end",[null,t],s),t},function(t){throw o.emit(n+"end",[t],s),t})})}var o=t("ee").get("fetch"),i=t(32),a=t(31);e.exports=o;var s=window,c="fetch-",f=c+"body-",u=["arrayBuffer","blob","json","text","formData"],d=s.Request,p=s.Response,l=s.fetch,h="prototype",m="nr@context";d&&p&&l&&(a(u,function(t,e){r(d[h],e,f),r(p[h],e,f)}),r(s,"fetch",c),o.on(c+"end",function(t,e){var n=this;if(e){var r=e.headers.get("content-length");null!==r&&(n.rxSize=r),o.emit(c+"done",[null,e],n)}else o.emit(c+"done",[t],n)}))},{}],9:[function(t,e,n){var r=t("ee").get("history"),o=t("wrap-function")(r);e.exports=r;var i=window.history&&window.history.constructor&&window.history.constructor.prototype,a=window.history;i&&i.pushState&&i.replaceState&&(a=i),o.inPlace(a,["pushState","replaceState"],"-")},{}],10:[function(t,e,n){function r(t){function e(){f.emit("jsonp-end",[],l),t.removeEventListener("load",e,c(!1)),t.removeEventListener("error",n,c(!1))}function n(){f.emit("jsonp-error",[],l),f.emit("jsonp-end",[],l),t.removeEventListener("load",e,c(!1)),t.removeEventListener("error",n,c(!1))}var r=t&&"string"==typeof t.nodeName&&"script"===t.nodeName.toLowerCase();if(r){var o="function"==typeof t.addEventListener;if(o){var a=i(t.src);if(a){var d=s(a),p="function"==typeof d.parent[d.key];if(p){var l={};u.inPlace(d.parent,[d.key],"cb-",l),t.addEventListener("load",e,c(!1)),t.addEventListener("error",n,c(!1)),f.emit("new-jsonp",[t.src],l)}}}}}function o(){return"addEventListener"in window}function i(t){var e=t.match(d);return e?e[1]:null}function a(t,e){var n=t.match(l),r=n[1],o=n[3];return o?a(o,e[r]):e[r]}function s(t){var e=t.match(p);return e&&e.length>=3?{key:e[2],parent:a(e[1],window)}:{key:t,parent:window}}var c=t(23),f=t("ee").get("jsonp"),u=t("wrap-function")(f);if(e.exports=f,o()){var d=/[?&](?:callback|cb)=([^&#]+)/,p=/(.*)\.([^.]+)/,l=/^(\w+)(\.|$)(.*)$/,h=["appendChild","insertBefore","replaceChild"];Node&&Node.prototype&&Node.prototype.appendChild?u.inPlace(Node.prototype,h,"dom-"):(u.inPlace(HTMLElement.prototype,h,"dom-"),u.inPlace(HTMLHeadElement.prototype,h,"dom-"),u.inPlace(HTMLBodyElement.prototype,h,"dom-")),f.on("dom-start",function(t){r(t[0])})}},{}],11:[function(t,e,n){var r=t("ee").get("mutation"),o=t("wrap-function")(r),i=NREUM.o.MO;e.exports=r,i&&(window.MutationObserver=function(t){return this instanceof i?new i(o(t,"fn-")):i.apply(this,arguments)},MutationObserver.prototype=i.prototype)},{}],12:[function(t,e,n){function r(t){var e=i.context(),n=s(t,"executor-",e,null,!1),r=new f(n);return i.context(r).getCtx=function(){return e},r}var o=t("wrap-function"),i=t("ee").get("promise"),a=t("ee").getOrSetContext,s=o(i),c=t(31),f=NREUM.o.PR;e.exports=i,f&&(window.Promise=r,["all","race"].forEach(function(t){var e=f[t];f[t]=function(n){function r(t){return function(){i.emit("propagate",[null,!o],a,!1,!1),o=o||!t}}var o=!1;c(n,function(e,n){Promise.resolve(n).then(r("all"===t),r(!1))});var a=e.apply(f,arguments),s=f.resolve(a);return s}}),["resolve","reject"].forEach(function(t){var e=f[t];f[t]=function(t){var n=e.apply(f,arguments);return t!==n&&i.emit("propagate",[t,!0],n,!1,!1),n}}),f.prototype["catch"]=function(t){return this.then(null,t)},f.prototype=Object.create(f.prototype,{constructor:{value:r}}),c(Object.getOwnPropertyNames(f),function(t,e){try{r[e]=f[e]}catch(n){}}),o.wrapInPlace(f.prototype,"then",function(t){return function(){var e=this,n=o.argsToArray.apply(this,arguments),r=a(e);r.promise=e,n[0]=s(n[0],"cb-",r,null,!1),n[1]=s(n[1],"cb-",r,null,!1);var c=t.apply(this,n);return r.nextPromise=c,i.emit("propagate",[e,!0],c,!1,!1),c}}),i.on("executor-start",function(t){t[0]=s(t[0],"resolve-",this,null,!1),t[1]=s(t[1],"resolve-",this,null,!1)}),i.on("executor-err",function(t,e,n){t[1](n)}),i.on("cb-end",function(t,e,n){i.emit("propagate",[n,!0],this.nextPromise,!1,!1)}),i.on("propagate",function(t,e,n){this.getCtx&&!e||(this.getCtx=function(){if(t instanceof Promise)var e=i.context(t);return e&&e.getCtx?e.getCtx():this})}),r.toString=function(){return""+f})},{}],13:[function(t,e,n){var r=t("ee").get("raf"),o=t("wrap-function")(r),i="equestAnimationFrame";e.exports=r,o.inPlace(window,["r"+i,"mozR"+i,"webkitR"+i,"msR"+i],"raf-"),r.on("raf-start",function(t){t[0]=o(t[0],"fn-")})},{}],14:[function(t,e,n){function r(t,e,n){t[0]=a(t[0],"fn-",null,n)}function o(t,e,n){this.method=n,this.timerDuration=isNaN(t[1])?0:+t[1],t[0]=a(t[0],"fn-",this,n)}var i=t("ee").get("timer"),a=t("wrap-function")(i),s="setTimeout",c="setInterval",f="clearTimeout",u="-start",d="-";e.exports=i,a.inPlace(window,[s,"setImmediate"],s+d),a.inPlace(window,[c],c+d),a.inPlace(window,[f,"clearImmediate"],f+d),i.on(c+u,r),i.on(s+u,o)},{}],15:[function(t,e,n){function r(t,e){d.inPlace(e,["onreadystatechange"],"fn-",s)}function o(){var t=this,e=u.context(t);t.readyState>3&&!e.resolved&&(e.resolved=!0,u.emit("xhr-resolved",[],t)),d.inPlace(t,y,"fn-",s)}function i(t){x.push(t),m&&(E?E.then(a):w?w(a):(R=-R,O.data=R))}function a(){for(var t=0;t<x.length;t++)r([],x[t]);x.length&&(x=[])}function s(t,e){return e}function c(t,e){for(var n in t)e[n]=t[n];return e}t(7);var f=t("ee"),u=f.get("xhr"),d=t("wrap-function")(u),p=t(23),l=NREUM.o,h=l.XHR,m=l.MO,v=l.PR,w=l.SI,g="readystatechange",y=["onload","onerror","onabort","onloadstart","onloadend","onprogress","ontimeout"],x=[];e.exports=u;var b=window.XMLHttpRequest=function(t){var e=new h(t);try{u.emit("new-xhr",[e],e),e.addEventListener(g,o,p(!1))}catch(n){try{u.emit("internal-error",[n])}catch(r){}}return e};if(c(h,b),b.prototype=h.prototype,d.inPlace(b.prototype,["open","send"],"-xhr-",s),u.on("send-xhr-start",function(t,e){r(t,e),i(e)}),u.on("open-xhr-start",r),m){var E=v&&v.resolve();if(!w&&!v){var R=1,O=document.createTextNode(R);new m(a).observe(O,{characterData:!0})}}else f.on("fn-end",function(t){t[0]&&t[0].type===g||a()})},{}],16:[function(t,e,n){function r(t){if(!s(t))return null;var e=window.NREUM;if(!e.loader_config)return null;var n=(e.loader_config.accountID||"").toString()||null,r=(e.loader_config.agentID||"").toString()||null,f=(e.loader_config.trustKey||"").toString()||null;if(!n||!r)return null;var h=l.generateSpanId(),m=l.generateTraceId(),v=Date.now(),w={spanId:h,traceId:m,timestamp:v};return(t.sameOrigin||c(t)&&p())&&(w.traceContextParentHeader=o(h,m),w.traceContextStateHeader=i(h,v,n,r,f)),(t.sameOrigin&&!u()||!t.sameOrigin&&c(t)&&d())&&(w.newrelicHeader=a(h,m,v,n,r,f)),w}function o(t,e){return"00-"+e+"-"+t+"-01"}function i(t,e,n,r,o){var i=0,a="",s=1,c="",f="";return o+"@nr="+i+"-"+s+"-"+n+"-"+r+"-"+t+"-"+a+"-"+c+"-"+f+"-"+e}function a(t,e,n,r,o,i){var a="btoa"in window&&"function"==typeof window.btoa;if(!a)return null;var s={v:[0,1],d:{ty:"Browser",ac:r,ap:o,id:t,tr:e,ti:n}};return i&&r!==i&&(s.d.tk=i),btoa(JSON.stringify(s))}function s(t){return f()&&c(t)}function c(t){var e=!1,n={};if("init"in NREUM&&"distributed_tracing"in NREUM.init&&(n=NREUM.init.distributed_tracing),t.sameOrigin)e=!0;else if(n.allowed_origins instanceof Array)for(var r=0;r<n.allowed_origins.length;r++){var o=h(n.allowed_origins[r]);if(t.hostname===o.hostname&&t.protocol===o.protocol&&t.port===o.port){e=!0;break}}return e}function f(){return"init"in NREUM&&"distributed_tracing"in NREUM.init&&!!NREUM.init.distributed_tracing.enabled}function u(){return"init"in NREUM&&"distributed_tracing"in NREUM.init&&!!NREUM.init.distributed_tracing.exclude_newrelic_header}function d(){return"init"in NREUM&&"distributed_tracing"in NREUM.init&&NREUM.init.distributed_tracing.cors_use_newrelic_header!==!1}function p(){return"init"in NREUM&&"distributed_tracing"in NREUM.init&&!!NREUM.init.distributed_tracing.cors_use_tracecontext_headers}var l=t(28),h=t(18);e.exports={generateTracePayload:r,shouldGenerateTrace:s}},{}],17:[function(t,e,n){function r(t){var e=this.params,n=this.metrics;if(!this.ended){this.ended=!0;for(var r=0;r<p;r++)t.removeEventListener(d[r],this.listener,!1);return e.protocol&&"data"===e.protocol?void g("Ajax/DataUrl/Excluded"):void(e.aborted||(n.duration=a.now()-this.startTime,this.loadCaptureCalled||4!==t.readyState?null==e.status&&(e.status=0):i(this,t),n.cbTime=this.cbTime,s("xhr",[e,n,this.startTime,this.endTime,"xhr"],this)))}}function o(t,e){var n=c(e),r=t.params;r.hostname=n.hostname,r.port=n.port,r.protocol=n.protocol,r.host=n.hostname+":"+n.port,r.pathname=n.pathname,t.parsedOrigin=n,t.sameOrigin=n.sameOrigin}function i(t,e){t.params.status=e.status;var n=v(e,t.lastSize);if(n&&(t.metrics.rxSize=n),t.sameOrigin){var r=e.getResponseHeader("X-NewRelic-App-Data");r&&(t.params.cat=r.split(", ").pop())}t.loadCaptureCalled=!0}var a=t("loader");if(a.xhrWrappable&&!a.disabled){var s=t("handle"),c=t(18),f=t(16).generateTracePayload,u=t("ee"),d=["load","error","abort","timeout"],p=d.length,l=t("id"),h=t(24),m=t(22),v=t(19),w=t(23),g=t(25).recordSupportability,y=NREUM.o.REQ,x=window.XMLHttpRequest;a.features.xhr=!0,t(15),t(8),u.on("new-xhr",function(t){var e=this;e.totalCbs=0,e.called=0,e.cbTime=0,e.end=r,e.ended=!1,e.xhrGuids={},e.lastSize=null,e.loadCaptureCalled=!1,e.params=this.params||{},e.metrics=this.metrics||{},t.addEventListener("load",function(n){i(e,t)},w(!1)),h&&(h>34||h<10)||t.addEventListener("progress",function(t){e.lastSize=t.loaded},w(!1))}),u.on("open-xhr-start",function(t){this.params={method:t[0]},o(this,t[1]),this.metrics={}}),u.on("open-xhr-end",function(t,e){"loader_config"in NREUM&&"xpid"in NREUM.loader_config&&this.sameOrigin&&e.setRequestHeader("X-NewRelic-ID",NREUM.loader_config.xpid);var n=f(this.parsedOrigin);if(n){var r=!1;n.newrelicHeader&&(e.setRequestHeader("newrelic",n.newrelicHeader),r=!0),n.traceContextParentHeader&&(e.setRequestHeader("traceparent",n.traceContextParentHeader),n.traceContextStateHeader&&e.setRequestHeader("tracestate",n.traceContextStateHeader),r=!0),r&&(this.dt=n)}}),u.on("send-xhr-start",function(t,e){var n=this.metrics,r=t[0],o=this;if(n&&r){var i=m(r);i&&(n.txSize=i)}this.startTime=a.now(),this.listener=function(t){try{"abort"!==t.type||o.loadCaptureCalled||(o.params.aborted=!0),("load"!==t.type||o.called===o.totalCbs&&(o.onloadCalled||"function"!=typeof e.onload))&&o.end(e)}catch(n){try{u.emit("internal-error",[n])}catch(r){}}};for(var s=0;s<p;s++)e.addEventListener(d[s],this.listener,w(!1))}),u.on("xhr-cb-time",function(t,e,n){this.cbTime+=t,e?this.onloadCalled=!0:this.called+=1,this.called!==this.totalCbs||!this.onloadCalled&&"function"==typeof n.onload||this.end(n)}),u.on("xhr-load-added",function(t,e){var n=""+l(t)+!!e;this.xhrGuids&&!this.xhrGuids[n]&&(this.xhrGuids[n]=!0,this.totalCbs+=1)}),u.on("xhr-load-removed",function(t,e){var n=""+l(t)+!!e;this.xhrGuids&&this.xhrGuids[n]&&(delete this.xhrGuids[n],this.totalCbs-=1)}),u.on("xhr-resolved",function(){this.endTime=a.now()}),u.on("addEventListener-end",function(t,e){e instanceof x&&"load"===t[0]&&u.emit("xhr-load-added",[t[1],t[2]],e)}),u.on("removeEventListener-end",function(t,e){e instanceof x&&"load"===t[0]&&u.emit("xhr-load-removed",[t[1],t[2]],e)}),u.on("fn-start",function(t,e,n){e instanceof x&&("onload"===n&&(this.onload=!0),("load"===(t[0]&&t[0].type)||this.onload)&&(this.xhrCbStart=a.now()))}),u.on("fn-end",function(t,e){this.xhrCbStart&&u.emit("xhr-cb-time",[a.now()-this.xhrCbStart,this.onload,e],e)}),u.on("fetch-before-start",function(t){function e(t,e){var n=!1;return e.newrelicHeader&&(t.set("newrelic",e.newrelicHeader),n=!0),e.traceContextParentHeader&&(t.set("traceparent",e.traceContextParentHeader),e.traceContextStateHeader&&t.set("tracestate",e.traceContextStateHeader),n=!0),n}var n,r=t[1]||{};"string"==typeof t[0]?n=t[0]:t[0]&&t[0].url?n=t[0].url:window.URL&&t[0]&&t[0]instanceof URL&&(n=t[0].href),n&&(this.parsedOrigin=c(n),this.sameOrigin=this.parsedOrigin.sameOrigin);var o=f(this.parsedOrigin);if(o&&(o.newrelicHeader||o.traceContextParentHeader))if("string"==typeof t[0]||window.URL&&t[0]&&t[0]instanceof URL){var i={};for(var a in r)i[a]=r[a];i.headers=new Headers(r.headers||{}),e(i.headers,o)&&(this.dt=o),t.length>1?t[1]=i:t.push(i)}else t[0]&&t[0].headers&&e(t[0].headers,o)&&(this.dt=o)}),u.on("fetch-start",function(t,e){this.params={},this.metrics={},this.startTime=a.now(),this.dt=e,t.length>=1&&(this.target=t[0]),t.length>=2&&(this.opts=t[1]);var n,r=this.opts||{},i=this.target;if("string"==typeof i?n=i:"object"==typeof i&&i instanceof y?n=i.url:window.URL&&"object"==typeof i&&i instanceof URL&&(n=i.href),o(this,n),"data"!==this.params.protocol){var s=(""+(i&&i instanceof y&&i.method||r.method||"GET")).toUpperCase();this.params.method=s,this.txSize=m(r.body)||0}}),u.on("fetch-done",function(t,e){if(this.endTime=a.now(),this.params||(this.params={}),"data"===this.params.protocol)return void g("Ajax/DataUrl/Excluded");this.params.status=e?e.status:0;var n;"string"==typeof this.rxSize&&this.rxSize.length>0&&(n=+this.rxSize);var r={txSize:this.txSize,rxSize:n,duration:a.now()-this.startTime};s("xhr",[this.params,r,this.startTime,this.endTime,"fetch"],this)})}},{}],18:[function(t,e,n){var r={};e.exports=function(t){if(t in r)return r[t];if(0===(t||"").indexOf("data:"))return{protocol:"data"};var e=document.createElement("a"),n=window.location,o={};e.href=t,o.port=e.port;var i=e.href.split("://");!o.port&&i[1]&&(o.port=i[1].split("/")[0].split("@").pop().split(":")[1]),o.port&&"0"!==o.port||(o.port="https"===i[0]?"443":"80"),o.hostname=e.hostname||n.hostname,o.pathname=e.pathname,o.protocol=i[0],"/"!==o.pathname.charAt(0)&&(o.pathname="/"+o.pathname);var a=!e.protocol||":"===e.protocol||e.protocol===n.protocol,s=e.hostname===document.domain&&e.port===n.port;return o.sameOrigin=a&&(!e.hostname||s),"/"===o.pathname&&(r[t]=o),o}},{}],19:[function(t,e,n){function r(t,e){var n=t.responseType;return"json"===n&&null!==e?e:"arraybuffer"===n||"blob"===n||"json"===n?o(t.response):"text"===n||""===n||void 0===n?o(t.responseText):void 0}var o=t(22);e.exports=r},{}],20:[function(t,e,n){function r(){}function o(t,e,n,r){return function(){return u.recordSupportability("API/"+e+"/called"),i(t+e,[f.now()].concat(s(arguments)),n?null:this,r),n?void 0:this}}var i=t("handle"),a=t(31),s=t(32),c=t("ee").get("tracer"),f=t("loader"),u=t(25),d=NREUM;"undefined"==typeof window.newrelic&&(newrelic=d);var p=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],l="api-",h=l+"ixn-";a(p,function(t,e){d[e]=o(l,e,!0,"api")}),d.addPageAction=o(l,"addPageAction",!0),d.setCurrentRouteName=o(l,"routeName",!0),e.exports=newrelic,d.interaction=function(){return(new r).get()};var m=r.prototype={createTracer:function(t,e){var n={},r=this,o="function"==typeof e;return i(h+"tracer",[f.now(),t,n],r),function(){if(c.emit((o?"":"no-")+"fn-start",[f.now(),r,o],n),o)try{return e.apply(this,arguments)}catch(t){throw c.emit("fn-err",[arguments,this,t],n),t}finally{c.emit("fn-end",[f.now()],n)}}}};a("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(t,e){m[e]=o(h,e)}),newrelic.noticeError=function(t,e){"string"==typeof t&&(t=new Error(t)),u.recordSupportability("API/noticeError/called"),i("err",[t,f.now(),!1,e])}},{}],21:[function(t,e,n){function r(t){if(NREUM.init){for(var e=NREUM.init,n=t.split("."),r=0;r<n.length-1;r++)if(e=e[n[r]],"object"!=typeof e)return;return e=e[n[n.length-1]]}}e.exports={getConfiguration:r}},{}],22:[function(t,e,n){e.exports=function(t){if("string"==typeof t&&t.length)return t.length;if("object"==typeof t){if("undefined"!=typeof ArrayBuffer&&t instanceof ArrayBuffer&&t.byteLength)return t.byteLength;if("undefined"!=typeof Blob&&t instanceof Blob&&t.size)return t.size;if(!("undefined"!=typeof FormData&&t instanceof FormData))try{return JSON.stringify(t).length}catch(e){return}}}},{}],23:[function(t,e,n){var r=!1;try{var o=Object.defineProperty({},"passive",{get:function(){r=!0}});window.addEventListener("testPassive",null,o),window.removeEventListener("testPassive",null,o)}catch(i){}e.exports=function(t){return r?{passive:!0,capture:!!t}:!!t}},{}],24:[function(t,e,n){var r=0,o=navigator.userAgent.match(/Firefox[\/\s](\d+\.\d+)/);o&&(r=+o[1]),e.exports=r},{}],25:[function(t,e,n){function r(t,e){var n=[a,t,{name:t},e];return i("storeMetric",n,null,"api"),n}function o(t,e){var n=[s,t,{name:t},e];return i("storeEventMetrics",n,null,"api"),n}var i=t("handle"),a="sm",s="cm";e.exports={constants:{SUPPORTABILITY_METRIC:a,CUSTOM_METRIC:s},recordSupportability:r,recordCustom:o}},{}],26:[function(t,e,n){function r(){return s.exists&&performance.now?Math.round(performance.now()):(i=Math.max((new Date).getTime(),i))-a}function o(){return i}var i=(new Date).getTime(),a=i,s=t(33);e.exports=r,e.exports.offset=a,e.exports.getLastTimestamp=o},{}],27:[function(t,e,n){function r(t,e){var n=t.getEntries();n.forEach(function(t){"first-paint"===t.name?l("timing",["fp",Math.floor(t.startTime)]):"first-contentful-paint"===t.name&&l("timing",["fcp",Math.floor(t.startTime)])})}function o(t,e){var n=t.getEntries();if(n.length>0){var r=n[n.length-1];if(f&&f<r.startTime)return;var o=[r],i=a({});i&&o.push(i),l("lcp",o)}}function i(t){t.getEntries().forEach(function(t){t.hadRecentInput||l("cls",[t])})}function a(t){var e=navigator.connection||navigator.mozConnection||navigator.webkitConnection;if(e)return e.type&&(t["net-type"]=e.type),e.effectiveType&&(t["net-etype"]=e.effectiveType),e.rtt&&(t["net-rtt"]=e.rtt),e.downlink&&(t["net-dlink"]=e.downlink),t}function s(t){if(t instanceof w&&!y){var e=Math.round(t.timeStamp),n={type:t.type};a(n),e<=h.now()?n.fid=h.now()-e:e>h.offset&&e<=Date.now()?(e-=h.offset,n.fid=h.now()-e):e=h.now(),y=!0,l("timing",["fi",e,n])}}function c(t){"hidden"===t&&(f=h.now(),l("pageHide",[f]))}if(!("init"in NREUM&&"page_view_timing"in NREUM.init&&"enabled"in NREUM.init.page_view_timing&&NREUM.init.page_view_timing.enabled===!1)){var f,u,d,p,l=t("handle"),h=t("loader"),m=t(30),v=t(23),w=NREUM.o.EV;if("PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver){u=new PerformanceObserver(r);try{u.observe({entryTypes:["paint"]})}catch(g){}d=new PerformanceObserver(o);try{d.observe({entryTypes:["largest-contentful-paint"]})}catch(g){}p=new PerformanceObserver(i);try{p.observe({type:"layout-shift",buffered:!0})}catch(g){}}if("addEventListener"in document){var y=!1,x=["click","keydown","mousedown","pointerdown","touchstart"];x.forEach(function(t){document.addEventListener(t,s,v(!1))})}m(c)}},{}],28:[function(t,e,n){function r(){function t(){return e?15&e[n++]:16*Math.random()|0}var e=null,n=0,r=window.crypto||window.msCrypto;r&&r.getRandomValues&&(e=r.getRandomValues(new Uint8Array(31)));for(var o,i="xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx",a="",s=0;s<i.length;s++)o=i[s],"x"===o?a+=t().toString(16):"y"===o?(o=3&t()|8,a+=o.toString(16)):a+=o;return a}function o(){return a(16)}function i(){return a(32)}function a(t){function e(){return n?15&n[r++]:16*Math.random()|0}var n=null,r=0,o=window.crypto||window.msCrypto;o&&o.getRandomValues&&Uint8Array&&(n=o.getRandomValues(new Uint8Array(t)));for(var i=[],a=0;a<t;a++)i.push(e().toString(16));return i.join("")}e.exports={generateUuid:r,generateSpanId:o,generateTraceId:i}},{}],29:[function(t,e,n){function r(t,e){if(!o)return!1;if(t!==o)return!1;if(!e)return!0;if(!i)return!1;for(var n=i.split("."),r=e.split("."),a=0;a<r.length;a++)if(r[a]!==n[a])return!1;return!0}var o=null,i=null,a=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var s=navigator.userAgent,c=s.match(a);c&&s.indexOf("Chrome")===-1&&s.indexOf("Chromium")===-1&&(o="Safari",i=c[1])}e.exports={agent:o,version:i,match:r}},{}],30:[function(t,e,n){function r(t){function e(){t(s&&document[s]?document[s]:document[i]?"hidden":"visible")}"addEventListener"in document&&a&&document.addEventListener(a,e,o(!1))}var o=t(23);e.exports=r;var i,a,s;"undefined"!=typeof document.hidden?(i="hidden",a="visibilitychange",s="visibilityState"):"undefined"!=typeof document.msHidden?(i="msHidden",a="msvisibilitychange"):"undefined"!=typeof document.webkitHidden&&(i="webkitHidden",a="webkitvisibilitychange",s="webkitVisibilityState")},{}],31:[function(t,e,n){function r(t,e){var n=[],r="",i=0;for(r in t)o.call(t,r)&&(n[i]=e(r,t[r]),i+=1);return n}var o=Object.prototype.hasOwnProperty;e.exports=r},{}],32:[function(t,e,n){function r(t,e,n){e||(e=0),"undefined"==typeof n&&(n=t?t.length:0);for(var r=-1,o=n-e||0,i=Array(o<0?0:o);++r<o;)i[r]=t[e+r];return i}e.exports=r},{}],33:[function(t,e,n){e.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(t,e,n){function r(){}function o(t){function e(t){return t&&t instanceof r?t:t?f(t,c,a):a()}function n(n,r,o,i,a){if(a!==!1&&(a=!0),!l.aborted||i){t&&a&&t(n,r,o);for(var s=e(o),c=m(n),f=c.length,u=0;u<f;u++)c[u].apply(s,r);var p=d[y[n]];return p&&p.push([x,n,r,s]),s}}function i(t,e){g[t]=m(t).concat(e)}function h(t,e){var n=g[t];if(n)for(var r=0;r<n.length;r++)n[r]===e&&n.splice(r,1)}function m(t){return g[t]||[]}function v(t){return p[t]=p[t]||o(n)}function w(t,e){l.aborted||u(t,function(t,n){e=e||"feature",y[n]=e,e in d||(d[e]=[])})}var g={},y={},x={on:i,addEventListener:i,removeEventListener:h,emit:n,get:v,listeners:m,context:e,buffer:w,abort:s,aborted:!1};return x}function i(t){return f(t,c,a)}function a(){return new r}function s(){(d.api||d.feature)&&(l.aborted=!0,d=l.backlog={})}var c="nr@context",f=t("gos"),u=t(31),d={},p={},l=e.exports=o();e.exports.getOrSetContext=i,l.backlog=d},{}],gos:[function(t,e,n){function r(t,e,n){if(o.call(t,e))return t[e];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(t,e,{value:r,writable:!0,enumerable:!1}),r}catch(i){}return t[e]=r,r}var o=Object.prototype.hasOwnProperty;e.exports=r},{}],handle:[function(t,e,n){function r(t,e,n,r){o.buffer([t],r),o.emit(t,e,n)}var o=t("ee").get("handle");e.exports=r,r.ee=o},{}],id:[function(t,e,n){function r(t){var e=typeof t;return!t||"object"!==e&&"function"!==e?-1:t===window?0:a(t,i,function(){return o++})}var o=1,i="nr@id",a=t("gos");e.exports=r},{}],loader:[function(t,e,n){function r(){if(!T++){var t=O.info=NREUM.info,e=m.getElementsByTagName("script")[0];if(setTimeout(f.abort,3e4),!(t&&t.licenseKey&&t.applicationID&&e))return f.abort();c(E,function(e,n){t[e]||(t[e]=n)});var n=a();s("mark",["onload",n+O.offset],null,"api"),s("timing",["load",n]);var r=m.createElement("script");0===t.agent.indexOf("http://")||0===t.agent.indexOf("https://")?r.src=t.agent:r.src=l+"://"+t.agent,e.parentNode.insertBefore(r,e)}}function o(){"complete"===m.readyState&&i()}function i(){s("mark",["domContent",a()+O.offset],null,"api")}var a=t(26),s=t("handle"),c=t(31),f=t("ee"),u=t(29),d=t(21),p=t(23),l=d.getConfiguration("ssl")===!1?"http":"https",h=window,m=h.document,v="addEventListener",w="attachEvent",g=h.XMLHttpRequest,y=g&&g.prototype,x=!1;NREUM.o={ST:setTimeout,SI:h.setImmediate,CT:clearTimeout,XHR:g,REQ:h.Request,EV:h.Event,PR:h.Promise,MO:h.MutationObserver};var b=""+location,E={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-spa-1216.min.js"},R=g&&y&&y[v]&&!/CriOS/.test(navigator.userAgent),O=e.exports={offset:a.getLastTimestamp(),now:a,origin:b,features:{},xhrWrappable:R,userAgent:u,disabled:x};if(!x){t(20),t(27),m[v]?(m[v]("DOMContentLoaded",i,p(!1)),h[v]("load",r,p(!1))):(m[w]("onreadystatechange",o),h[w]("onload",r)),s("mark",["firstbyte",a.getLastTimestamp()],null,"api");var T=0}},{}],"wrap-function":[function(t,e,n){function r(t,e){function n(e,n,r,c,f){function nrWrapper(){var i,a,u,p;try{a=this,i=d(arguments),u="function"==typeof r?r(i,a):r||{}}catch(l){o([l,"",[i,a,c],u],t)}s(n+"start",[i,a,c],u,f);try{return p=e.apply(a,i)}catch(h){throw s(n+"err",[i,a,h],u,f),h}finally{s(n+"end",[i,a,p],u,f)}}return a(e)?e:(n||(n=""),nrWrapper[p]=e,i(e,nrWrapper,t),nrWrapper)}function r(t,e,r,o,i){r||(r="");var s,c,f,u="-"===r.charAt(0);for(f=0;f<e.length;f++)c=e[f],s=t[c],a(s)||(t[c]=n(s,u?c+r:r,o,c,i))}function s(n,r,i,a){if(!h||e){var s=h;h=!0;try{t.emit(n,r,i,e,a)}catch(c){o([c,n,r,i],t)}h=s}}return t||(t=u),n.inPlace=r,n.flag=p,n}function o(t,e){e||(e=u);try{e.emit("internal-error",t)}catch(n){}}function i(t,e,n){if(Object.defineProperty&&Object.keys)try{var r=Object.keys(t);return r.forEach(function(n){Object.defineProperty(e,n,{get:function(){return t[n]},set:function(e){return t[n]=e,e}})}),e}catch(i){o([i],n)}for(var a in t)l.call(t,a)&&(e[a]=t[a]);return e}function a(t){return!(t&&t instanceof Function&&t.apply&&!t[p])}function s(t,e){var n=e(t);return n[p]=t,i(t,n,u),n}function c(t,e,n){var r=t[e];t[e]=s(r,n)}function f(){for(var t=arguments.length,e=new Array(t),n=0;n<t;++n)e[n]=arguments[n];return e}var u=t("ee"),d=t(32),p="nr@original",l=Object.prototype.hasOwnProperty,h=!1;e.exports=r,e.exports.wrapFunction=s,e.exports.wrapInPlace=c,e.exports.argsToArray=f},{}]},{},["loader",2,17,5,3,4]);</script>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
        <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,500;0,700;1,400;1,500;1,700&amp;display=swap&amp;family=Farsan" rel="stylesheet">

        <!-- Hotjar Tracking Code for https://picoworkers.com/ -->
        <script>
            (function(h,o,t,j,a,r){
                h.hj=h.hj||function(){(h.hj.q=h.hj.q||[]).push(arguments)};
                h._hjSettings={hjid:2261922,hjsv:6};
                a=o.getElementsByTagName('head')[0];
                r=o.createElement('script');r.async=1;
                r.src=t+h._hjSettings.hjid+j+h._hjSettings.hjsv;
                a.appendChild(r);
            })(window,document,'https://static.hotjar.com/c/hotjar-','.js?sv=');
        </script>

        <script>
            var arguments = {};
                        arguments = { userId: 'd647f565' };
                        window.dataLayer = window.dataLayer || [];
            window.dataLayer.push(arguments);
        </script>

        <!-- Google Tag Manager -->
        <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
        new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
        j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
        'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
        })(window,document,'script','dataLayer','GTM-P6G6QRQ');</script>
        <!-- End Google Tag Manager -->

                    <link rel="stylesheet" href="/assets/css/app.min.css?v=202208231801"/>
            <script src="/assets/js/jquery.min.js"></script>
            <script src="/assets/js/pico-vendor.min.js?v=202208191430"></script>
            <script src="/assets/js/pico-app.min.js?v=202208251349"></script>
        
        <!--[if lt IE 9]>
        <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
        <script src="/assets/js/vendor/respond.min.js"></script>
        <script src="/assets/js/vendor/PIE.js"></script>
        <![endif]-->

        <script>
            var csrf_token = 'dc43f1d538169f21226f6ac90201fd80';
            var systemAlert = '85';
            var tasks_ok = '17';
        </script>

            </head>

    <body class="">
        <!-- Google Tag Manager (noscript) -->
        <noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-P6G6QRQ"
        height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
        <!-- End Google Tag Manager (noscript) -->

        <div class="site d-flex flex-column min-vh-100">
              <nav class="navbar navbar-expand-lg navbar-light">
  <div class="container-fluid container-fluid--max-lg">
    <img class="navbar__gradient" src="/gradient.php">
    <a class="navbar-brand" href="/">
      <img src="/assets/images/logo.svg" alt="PicoWorkers" class="navbar-brand__regular">
      <img src="/assets/images/logo-dark-mode.svg" alt="PicoWorkers" class="navbar-brand__dark-mode d-none">
    </a>

    <div class="d-none d-lg-block flex-grow-0">
      <ul class="navbar-nav mr-auto">
                <li class="nav-item dropdown">
          <a class="nav-link" href="/worker/gigs.php" data-toggle="dropdown">
            <span>
              Gigs <i class="fas fa-caret-down"></i>
            </span>
            <sup class="symbol symbol--warning pb-0">New</sup>
                      </a>
          <div class="dropdown-menu mt-3">
            <a class="dropdown-item d-flex align-items-center justify-content-between text-body" href="/gigs.php">Browse Gigs</a>
            <a
              class="dropdown-item d-flex align-items-center justify-content-between text-body"
              href="/worker/gigs.php"
                          >
              My Posted Gigs
                          </a>
          </div>
        </li>

                  <li class="nav-item dropdown">
            <a class="nav-link" href="/worker.php" data-toggle="dropdown"><span>MicroJobs <i class="fas fa-caret-down"></i></span></a>
            <div class="dropdown-menu mt-3">
              <a class="dropdown-item d-flex align-items-center justify-content-between text-body" href="/jobs.php">Find Jobs</a>
              <a class="dropdown-item d-flex align-items-center justify-content-between text-body" href="/worker.php">Finished Tasks <span>29</span></a>
              <hr class="m-0">
              <div class="py-2 px-4">
                <div class="py-2 mb-0 op-6 d-flex align-items-center justify-content-between">
                  <strong>satisfied + paid</strong>
                  <span>17</span>
                </div>
                <div class="py-2 mb-0 op-6 d-flex align-items-center justify-content-between">
                  <strong>pending review</strong>
                  <span>0</span>
                </div>
              </div>
            </div>
          </li>
        
        <li class="nav-item">
          <a class="nav-link" href="/wallet.php"><span>Wallet</span></a>
        </li>
      </ul>
    </div>

    <div class="navbar-right d-flex align-items-center">
      <ul class="nav align-items-center navbar-nav-2 nav--dynamic d-none d-lg-flex">

                  <a class="nav-link switch-profile-text switch-profile-text--desktop d-flex align-items-center flex-nowrap" href="#" data-change-profile-to="employer">
            <span>employer</span>
            <div class="zawp-toggle zawp-toggle--checked-last not-functional mx-2"><span class="zawp-toggle__switch m-0"></span></div>
            <span>worker</span>
          </a>
        
                  <li class="nav-item">
            <a class="nav-link" href="/tickets.php" data-tippy="true" data-tippy-content="support center">
              <i class="far fa-question-circle"></i>
            </a>
          </li>
                <li class="nav-item dropdown navbar__dropdown">
          <a class="nav-link notificationDropdown" href="#" data-toggle="dropdown" data-tippy="true" data-tippy-content="view notifications">
            <i class="far fa-bell"></i>
                      </a>
          <div class="notifications dropdown-menu dropdown-menu-right custom-scrollbar-css">
            <div class="notifications__inner">
                              <span class="notification">You don't have any notifications at the moment.</span>
                                        </div>
                      </div>
        </li>
        <li class="nav-item dropdown navbar__dropdown navbar__logs logs-dd">
          <a class="nav-link" href="#" data-toggle="dropdown"
            data-tippy="true"
            data-tippy-content="view logs"
          >
            <i class="fas fa-history"></i>
          </a>
          <div class="dropdown-menu dropdown-menu-right custom-scrollbar-css">
                                      <div class="dropdown-item d-block">
                                  <span class="logs-dd__desc">You submitted task 16539707214c37 | Small Job: Marketing Test Visit 1x</span>
                                <br>
                <span class="logs-dd__time">Jan 27, 2022 at 07:37</span>
              </div>
                                      <div class="see-all w-100 text-center pt-2 pb-2">
                <a href="/user-history.php#log-tab">See all</a>
              </div>
                      </div>
        </li>
      </ul>

      <button class="navbar-toggler ml-3" type="button" aria-expanded="false">
        <span class="navbar-toggler-icon"></span>
              </button>

      <ul class="d-none d-lg-block nav align-items-center navbar-nav-2">
        <li class="nav-item navbar-nav__profile profile-dropdown dropdown dropdown-stick">
          <a class="nav-link" href="#" data-toggle="dropdown" data-tippy="true" data-tippy-content="profile">
            <div class="d-flex align-items-center flex-nowrap">
              <img src="/assets/images/profile_no_image.gif" alt="Akki2703">
            </div>
          </a>
          <div class="dropdown-menu dropdown-menu-right">
            <span class="profile-dropdown__name">Hello, Akki2703</span>
            <span class="dropdown-hr mt-0"></span>
            <a class="dropdown-item" href="/account.php">Account Settings</a>
            <a class="dropdown-item" href="/Akki2703">My Profile</a>
            <a class="dropdown-item" href="/ranks.php">Workers ranking</a>
            <a class="dropdown-item" href="/auth/logout.php">Logout</a>
          </div>
        </li>
      </ul>
      <div class="setting-toggle navbar__dark-mode d-none d-sm-block" data-setting-toggle="darkmode">
        <input type="checkbox" id="darkModeNavToggle" class="toggle__input" >
        <label for="darkModeNavToggle" class="text-gray p-2 mb-0 setting-toggle__label-enable align-items-centerd-flex"
          data-tippy="true"
          data-tippy-content="dark mode"
        >
          <i class="fas fa-moon"></i>
        </label>
        <label for="darkModeNavToggle" class="text-gray p-2 mb-0 setting-toggle__label-disable align-items-center d-none"
          data-tippy="true"
          data-tippy-content="light mode"
        >
          <svg fill="#ffffff" xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 8.467 8.467"><path d="M 15.988281 0.98242188 A 1.0001 1.0001 0 0 0 15.886719 0.98828125 A 1.0001 1.0001 0 0 0 15 2 L 15 6.0019531 A 1.0002461 1.0002461 0 1 0 17 6.0019531 L 17 2 A 1.0001 1.0001 0 0 0 15.988281 0.98242188 z M 6.0898438 5.0878906 A 1.0001 1.0001 0 0 0 5.9863281 5.09375 A 1.0001 1.0001 0 0 0 5.3964844 6.8066406 L 8.2226562 9.6328125 A 1.0001 1.0001 0 1 0 9.6328125 8.2226562 L 6.8066406 5.3964844 A 1.0001 1.0001 0 0 0 6.0898438 5.0878906 z M 25.880859 5.09375 A 1.0001 1.0001 0 0 0 25.195312 5.3964844 L 22.367188 8.2226562 A 1.0001 1.0001 0 1 0 23.777344 9.6328125 L 26.603516 6.8066406 A 1.0001 1.0001 0 0 0 25.880859 5.09375 z M 16 8 A 7.9999995 7.9999995 0 0 0 8 16 A 7.9999995 7.9999995 0 0 0 16 24 A 7.9999995 7.9999995 0 0 0 24 16 A 7.9999995 7.9999995 0 0 0 16 8 z M 2 15 A 1.000252 1.000252 0 1 0 2 17 L 6.0019531 17 A 1.000252 1.000252 0 1 0 6.0019531 15 L 2 15 z M 25.998047 15 A 1.000252 1.000252 0 1 0 25.998047 17 L 30 17 A 1.000252 1.000252 0 1 0 30 15 L 25.998047 15 z M 23.060547 22.058594 A 1.0001 1.0001 0 0 0 22.957031 22.064453 A 1.0001 1.0001 0 0 0 22.367188 23.777344 L 25.195312 26.603516 A 1.0001 1.0001 0 1 0 26.603516 25.193359 L 23.777344 22.367188 A 1.0001 1.0001 0 0 0 23.060547 22.058594 z M 8.9101562 22.064453 A 1.0001 1.0001 0 0 0 8.2226562 22.367188 L 5.3964844 25.193359 A 1.0001 1.0001 0 1 0 6.8066406 26.603516 L 9.6328125 23.777344 A 1.0001 1.0001 0 0 0 8.9101562 22.064453 z M 15.982422 24.986328 A 1.0001 1.0001 0 0 0 15 25.998047 L 15 30 A 1.0002461 1.0002461 0 1 0 17 30 L 17 25.998047 A 1.0001 1.0001 0 0 0 15.982422 24.986328 z " paint-order="fill markers stroke" transform="scale(.26458)"/></svg>
        </label>
      </div>
              <a href="/jobs.php" class="d-none d-lg-block btn btn-primary btn-md navbar__post-job ml-4">Find Jobs</a>
          </div>
  </div>
</nav>

<div class="site-notice">
  <div class="container-fluid container-fluid--max">
    <div class="row align-items-center">
      <div class="col-sm-5 mb-2 mb-sm-0">
        <a href="/api/documentation.php">API</a>
        <span class="mx-1">|</span>
        <a href="/account.php#programs-offers">Refer a Friend</a>
              </div>
      <div class="col-sm-7 d-flex align-items-center justify-content-sm-end flex-wrap">
                  <div class="mb-0 mr-5 d-flex justify-content-center">
            <strong class="mr-2">Earned:</strong>
            <a href="/worker.php?filter=SATISFIED">
              <span id="earned-balance">$0.1235</span>
            </a>
          </div>
          <div class="mb-0 mr-5 d-flex justify-content-center">
            <strong class="mr-2">Pending:</strong>
            <a href="/worker.php?filter=PENDING">
              <span>$0.0000</span>
            </a>
          </div>
          <div class="mb-0 d-flex justify-content-center" data-tippy="true" data-tippy-content="The submit tasks interval is the time in seconds you have to wait between completing tasks. New workers start with 180 seconds. Not satisfied rated tasks gain a 20 second penalty, and system blocked spam proofs gain a 60 second penalty. Each satisfied task reduces the timer 10 seconds. Your task interval timer must be zero to withdraw. Higher level workers earn a buffer.">
            <strong class="mr-1"><i class="far fa-clock align-middle"></i></strong>
            <span id="earned-balance">370s</span>
          </div>
                      </div>
    </div>
  </div>
</div>


<div class="side-nav">
  <div class="side-nav__inner">
    <div class="side-nav__header d-flex align-items-center justify-content-between p-0">
      <ul class="nav align-items-center navbar-nav-2">
        <li class="nav-item navbar-nav__profile">
          <a class="nav-link" href="#">
            <div class="d-flex align-items-center flex-nowrap">
              <img src="/assets/images/profile_no_image.gif" alt="Akki2703" class="mr-3">
              <span>Hello, Akki2703</span>
            </div>
          </a>
        </li>
      </ul>
      <button class="navbar-btn--close btn btn-link ml-auto mr-0 p-4"><i class="pw-icon pw-icon-cross-2"></i></button>
    </div>
    <div class="nav flex-column pt-1">
      <li class="nav-item">
                  <a class="nav-link switch-profile-text d-flex align-items-center flex-nowrap" href="#" data-change-profile-to="employer">
            <span>employer</span>
            <div class="zawp-toggle zawp-toggle--checked-last not-functional mx-2"><span class="zawp-toggle__switch m-0"></span></div>
            <span>worker</span>
          </a>
              </li>
    </div>
    <div class="side-nav__body pt-3">
      <ul class="nav flex-column">
        <li class="nav-item position-relative" id="gigs-menu" style="width: fit-content;">
          <div class="list-group">
            <a href="#gigs-submenu" class="nav-link list-group-header border-0 pt-0" data-toggle="collapse" data-parent="#gigs-menu" >
              Gigs<i class="fa fa-caret-down mx-2"></i>
              <span class="symbol symbol--warning pb-0 px-2">New</span>
                          </a>
            <div class="collapse" id="gigs-submenu">
            <a class="ml-2 list-group-item small text-body border-0" href="/gigs.php">Browse Gigs</a>
            <a
              class="ml-2 list-group-item small text-body border-0 pt-0"
              href="/worker/gigs.php"
              style="width: fit-content;"
                          >
              My Posted Gigs
                          </a>
            </div>
          </div>
        </li>

        <li class="nav-item position-relative" id="microjobs-menu" style="width: fit-content;">
          <div class="list-group">
            <a href="#microjobs-submenu" class="nav-link list-group-header border-0 pt-0" data-toggle="collapse" data-parent="#microjobs-menu" >
              MicroJobs<i class="fa fa-caret-down mx-2"></i>
            </a>
                      <div class="collapse" id="microjobs-submenu">
                                    </div>
            </div>
          </li>
        
        <li class="nav-item">
          <a class="nav-link" href="/wallet.php"><span>Wallet</span></a>
        </li>
      </ul>
    </div>

    <div class="navbar-right d-flex align-items-center">
      <ul class="nav align-items-center navbar-nav-2 nav--dynamic d-none d-lg-flex">

                  <a class="nav-link switch-profile-text switch-profile-text--desktop d-flex align-items-center flex-nowrap" href="#" data-change-profile-to="employer">
            <span>employer</span>
            <div class="zawp-toggle zawp-toggle--checked-last not-functional mx-2"><span class="zawp-toggle__switch m-0"></span></div>
            <span>worker</span>
          </a>
        
                  <li class="nav-item">
            <a class="nav-link" href="/tickets.php" data-tippy="true" data-tippy-content="support center">
              <i class="far fa-question-circle"></i>
            </a>
          </li>
                <li class="nav-item dropdown navbar__dropdown">
          <a class="nav-link notificationDropdown" href="#" data-toggle="dropdown" data-tippy="true" data-tippy-content="view notifications">
            <i class="far fa-bell"></i>
                      </a>
          <div class="notifications dropdown-menu dropdown-menu-right custom-scrollbar-css">
            <div class="notifications__inner">
                              <span class="notification">You don't have any notifications at the moment.</span>
                                        </div>
                      </div>
        </li>
        <li class="nav-item dropdown navbar__dropdown navbar__logs logs-dd">
          <a class="nav-link" href="#" data-toggle="dropdown"
            data-tippy="true"
            data-tippy-content="view logs"
          >
            <i class="fas fa-history"></i>
          </a>
          <div class="dropdown-menu dropdown-menu-right custom-scrollbar-css">
                                      <div class="dropdown-item d-block">
                                  <span class="logs-dd__desc">You submitted task 16539707214c37 | Small Job: Marketing Test Visit 1x</span>
                                <br>
                <span class="logs-dd__time">Jan 27, 2022 at 07:37</span>
              </div>
                                      <div class="see-all w-100 text-center pt-2 pb-2">
                <a href="/user-history.php#log-tab">See all</a>
              </div>
                      </div>
        </li>
      </ul>

      <button class="navbar-toggler ml-3" type="button" aria-expanded="false">
        <span class="navbar-toggler-icon"></span>
              </button>

      <ul class="d-none d-lg-block nav align-items-center navbar-nav-2">
        <li class="nav-item navbar-nav__profile profile-dropdown dropdown dropdown-stick">
          <a class="nav-link" href="#" data-toggle="dropdown" data-tippy="true" data-tippy-content="profile">
            <div class="d-flex align-items-center flex-nowrap">
              <img src="/assets/images/profile_no_image.gif" alt="Akki2703">
            </div>
          </a>
          <div class="dropdown-menu dropdown-menu-right">
            <span class="profile-dropdown__name">Hello, Akki2703</span>
            <span class="dropdown-hr mt-0"></span>
            <a class="dropdown-item" href="/account.php">Account Settings</a>
            <a class="dropdown-item" href="/Akki2703">My Profile</a>
            <a class="dropdown-item" href="/ranks.php">Workers ranking</a>
            <a class="dropdown-item" href="/auth/logout.php">Logout</a>
          </div>
        </li>
      </ul>
      <div class="setting-toggle navbar__dark-mode d-none d-sm-block" data-setting-toggle="darkmode">
        <input type="checkbox" id="darkModeNavToggle" class="toggle__input" >
        <label for="darkModeNavToggle" class="text-gray p-2 mb-0 setting-toggle__label-enable align-items-centerd-flex"
          data-tippy="true"
          data-tippy-content="dark mode"
        >
          <i class="fas fa-moon"></i>
        </label>
        <label for="darkModeNavToggle" class="text-gray p-2 mb-0 setting-toggle__label-disable align-items-center d-none"
          data-tippy="true"
          data-tippy-content="light mode"
        >
          <svg fill="#ffffff" xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 8.467 8.467"><path d="M 15.988281 0.98242188 A 1.0001 1.0001 0 0 0 15.886719 0.98828125 A 1.0001 1.0001 0 0 0 15 2 L 15 6.0019531 A 1.0002461 1.0002461 0 1 0 17 6.0019531 L 17 2 A 1.0001 1.0001 0 0 0 15.988281 0.98242188 z M 6.0898438 5.0878906 A 1.0001 1.0001 0 0 0 5.9863281 5.09375 A 1.0001 1.0001 0 0 0 5.3964844 6.8066406 L 8.2226562 9.6328125 A 1.0001 1.0001 0 1 0 9.6328125 8.2226562 L 6.8066406 5.3964844 A 1.0001 1.0001 0 0 0 6.0898438 5.0878906 z M 25.880859 5.09375 A 1.0001 1.0001 0 0 0 25.195312 5.3964844 L 22.367188 8.2226562 A 1.0001 1.0001 0 1 0 23.777344 9.6328125 L 26.603516 6.8066406 A 1.0001 1.0001 0 0 0 25.880859 5.09375 z M 16 8 A 7.9999995 7.9999995 0 0 0 8 16 A 7.9999995 7.9999995 0 0 0 16 24 A 7.9999995 7.9999995 0 0 0 24 16 A 7.9999995 7.9999995 0 0 0 16 8 z M 2 15 A 1.000252 1.000252 0 1 0 2 17 L 6.0019531 17 A 1.000252 1.000252 0 1 0 6.0019531 15 L 2 15 z M 25.998047 15 A 1.000252 1.000252 0 1 0 25.998047 17 L 30 17 A 1.000252 1.000252 0 1 0 30 15 L 25.998047 15 z M 23.060547 22.058594 A 1.0001 1.0001 0 0 0 22.957031 22.064453 A 1.0001 1.0001 0 0 0 22.367188 23.777344 L 25.195312 26.603516 A 1.0001 1.0001 0 1 0 26.603516 25.193359 L 23.777344 22.367188 A 1.0001 1.0001 0 0 0 23.060547 22.058594 z M 8.9101562 22.064453 A 1.0001 1.0001 0 0 0 8.2226562 22.367188 L 5.3964844 25.193359 A 1.0001 1.0001 0 1 0 6.8066406 26.603516 L 9.6328125 23.777344 A 1.0001 1.0001 0 0 0 8.9101562 22.064453 z M 15.982422 24.986328 A 1.0001 1.0001 0 0 0 15 25.998047 L 15 30 A 1.0002461 1.0002461 0 1 0 17 30 L 17 25.998047 A 1.0001 1.0001 0 0 0 15.982422 24.986328 z " paint-order="fill markers stroke" transform="scale(.26458)"/></svg>
        </label>
      </div>
              <a href="/jobs.php" class="d-none d-lg-block btn btn-primary btn-md navbar__post-job ml-4">Find Jobs</a>
          </div>
  </div>
</nav>

<div class="site-notice">
  <div class="container-fluid container-fluid--max">
    <div class="row align-items-center">
      <div class="col-sm-5 mb-2 mb-sm-0">
        <a href="/api/documentation.php">API</a>
        <span class="mx-1">|</span>
        <a href="/account.php#programs-offers">Refer a Friend</a>
              </div>
      <div class="col-sm-7 d-flex align-items-center justify-content-sm-end flex-wrap">
                  <div class="mb-0 mr-5 d-flex justify-content-center">
            <strong class="mr-2">Earned:</strong>
            <a href="/worker.php?filter=SATISFIED">
              <span id="earned-balance">$0.1235</span>
            </a>
          </div>
          <div class="mb-0 mr-5 d-flex justify-content-center">
            <strong class="mr-2">Pending:</strong>
            <a href="/worker.php?filter=PENDING">
              <span>$0.0000</span>
            </a>
          </div>
          <div class="mb-0 d-flex justify-content-center" data-tippy="true" data-tippy-content="The submit tasks interval is the time in seconds you have to wait between completing tasks. New workers start with 180 seconds. Not satisfied rated tasks gain a 20 second penalty, and system blocked spam proofs gain a 60 second penalty. Each satisfied task reduces the timer 10 seconds. Your task interval timer must be zero to withdraw. Higher level workers earn a buffer.">
            <strong class="mr-1"><i class="far fa-clock align-middle"></i></strong>
            <span id="earned-balance">370s</span>
          </div>
                      </div>
    </div>
  </div>
</div>


<div class="side-nav">
  <div class="side-nav__inner">
    <div class="side-nav__header d-flex align-items-center justify-content-between p-0">
      <ul class="nav align-items-center navbar-nav-2">
        <li class="nav-item navbar-nav__profile">
          <a class="nav-link" href="#">
            <div class="d-flex align-items-center flex-nowrap">
              <img src="/assets/images/profile_no_image.gif" alt="Akki2703" class="mr-3">
              <span>Hello, Akki2703</span>
            </div>
          </a>
        </li>
      </ul>
      <button class="navbar-btn--close btn btn-link ml-auto mr-0 p-4"><i class="pw-icon pw-icon-cross-2"></i></button>
    </div>
    <div class="nav flex-column pt-1">
      <li class="nav-item">
                  <a class="nav-link switch-profile-text d-flex align-items-center flex-nowrap" href="#" data-change-profile-to="employer">
            <span>employer</span>
            <div class="zawp-toggle zawp-toggle--checked-last not-functional mx-2"><span class="zawp-toggle__switch m-0"></span></div>
            <span>worker</span>
          </a>
              </li>
    </div>
    <div class="side-nav__body pt-3">
      <ul class="nav flex-column">
        <li class="nav-item position-relative" id="gigs-menu" style="width: fit-content;">
          <div class="list-group">
            <a href="#gigs-submenu" class="nav-link list-group-header border-0 pt-0" data-toggle="collapse" data-parent="#gigs-menu" >
              Gigs<i class="fa fa-caret-down mx-2"></i>
              <span class="symbol symbol--warning pb-0 px-2">New</span>
                          </a>
            <div class="collapse" id="gigs-submenu">
            <a class="ml-2 list-group-item small text-body border-0" href="/gigs.php">Browse Gigs</a>
            <a
              class="ml-2 list-group-item small text-body border-0 pt-0"
              href="/worker/gigs.php"
              style="width: fit-content;"
                          >
              My Posted Gigs
                          </a>
            </div>
          </div>
        </li>

        <li class="nav-item position-relative" id="microjobs-menu" style="width: fit-content;">
          <div class="list-group">
            <a href="#microjobs-submenu" class="nav-link list-group-header border-0 pt-0" data-toggle="collapse" data-parent="#microjobs-menu" >
              MicroJobs<i class="fa fa-caret-down mx-2"></i>
            </a>
                      <div class="collapse" id="microjobs-submenu">
              <a class="ml-2 list-group-item small text-body border-0" href="/jobs.php">Find Jobs</a>
              <a class="ml-2 list-group-item small text-body border-0" href="/worker.php">Finished Tasks <span class="badge badge-primary ml-2">29</span></a>
              <span class="ml-2 list-group-item small text-gray border-0 font-italic">satisfied + paid <span class="badge badge-primary ml-2">17</span></span>
              <span class="ml-2 list-group-item small text-gray border-0 font-italic">pending review <span class="badge badge-primary ml-2">0</span></span>
            </div>
                    </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/wallet.php">Wallet</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/account.php">My Account</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/ranks.php">Rankings</a>
        </li>
        <li class="nav-item position-relative">
          <a class="nav-link" href="/tickets.php">Support Tickets</a>
                  </li>
        <li class="nav-item position-relative">
          <a class="nav-link notificationDropdown" href="/user-history.php">Notifications</a>
                  </li>
        <li class="nav-item">
          <a class="nav-link" href="/user-history.php#log-tab">Logs</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/auth/logout.php">Logout</a>
        </li>
      </ul>
    </div>
    <div class="side-nav__footer">
              <a href="/jobs.php" class="btn btn-primary btn-lg btn-block">Find Jobs</a>
          </div>
  </div>
</div>

                  <div class="mb-0 rounded-0 pw-banner align-items-center alert" style="">
      <span>This job is no longer available. Please, try another one.</span>
      <button type="button" class="close pw-banner-close" aria-label="Close">
        <span aria-hidden="true">&times;</span>
      </button>
    </div>
  
            <div class="container-fluid container-fluid--max">




        <div class="alert alert-with-icon pw-badge-info alert-dismissible fade show font-weight-medium system-alert-85 mt-3" data-alert="85" role="alert">
        <i class="svg-icon-emergency-green alert-icon"></i>
        Gig posting is now open to all expert workers regardless of KYC status
        <button type="button" class="close close-system-alert" data-dismiss="alert" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
  

</div>


            <div class="main">  <div class="container-fluid container-fluid--max">
    <div class="content-sidebar row justify-content-between">
      <aside class="sidebar col-md-4 order-md-2">
                  <a class="btn btn-success btn-lg btn-block mb-7" href="/tickets/new-ticket.php">OPEN NEW TICKET</a>
                <div class="d-flex align-items-center text-lg pb-2"><i class="pw-icon-info text-warning"></i><span class="pl-2">Info</span></div>
        <div class="p-4 bg-gray text-lg">
          Tickets are answered in 24 hours. Before opening a ticket, check our <a href="/faq.php">FAQ</a> documents.
          <p class="mt-3 font-weight-bold">Tickets Restrictions</p>
          <ul>
            <li>Up to 3 tickets can be open per hour.</li>
            <li>Up to 2 consecutive messages can be sent in a ticket. After that, no more messages can be sent until admins reply.</li>
            <li>Once the ticket is closed, it cannot be re-opened. A new one must be created.</li>
          </ul>
        </div>
      </aside>
      <!-- ./sidebar -->
      <div class="content-area col-md-8">
        <div class="sub-header mb-6">
          <a href="/tickets.php" class="btn btn-link btn-with-icon sub-header__back"><i class="pw-icon-arrow-left mr-2"></i> <span>Back</span></a>
          <h1 class="headline h2 mb-2">change of paypal account</h1>
          <p class="m-0">
            <span class="ticket-badge ticket-badge__closed mr-2">closed</span>
            <span class="ticket-badge bg-blue mr-2">2021-01-08</span>
            <span class="ticket-badge bg-blue">Problem with Account</span>
          </p>
        </div>

                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Akki2703</strong>
            <span>Jan 08, 2021 06:55</span>
          </div>
          <div class="card-body">
            i want to change my paypal account details how can i change it please tell me about that 
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Mars</strong>
            <span>Jan 08, 2021 07:41</span>
          </div>
          <div class="card-body">
            Hello<br />
<br />
Thanks for reaching us. To change your Picoworkers email address. Please select &quot;PASSWORD/EMAIL&quot; tab to change your email address<br />
https://prnt.sc/urodhu<br />
Add new email address<br />
Request a Token (this will be sent to your email) and submit.<br />
<br />
Regards,
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Akki2703</strong>
            <span>Jan 11, 2021 09:20</span>
          </div>
          <div class="card-body">
            i changed the email address but im still receiving withdrawl code on my old mail id <br />

                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Jean-Claude</strong>
            <span>Jan 11, 2021 09:33</span>
          </div>
          <div class="card-body">
            Hello,<br />
<br />
Kindly help us with your old and new email addresses. Also, be sure to save your profile settings after doing the changes. 
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Akki2703</strong>
            <span>Jan 11, 2021 14:37</span>
          </div>
          <div class="card-body">
            old email - <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="6208031b0309090b5055525122050f030b0e4c010d0f">[email&#160;protected]</a><br />
new email - <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="edac86858481889e85808c819b84948cdfdadddead8a808c8481c38e8280">[email&#160;protected]</a>
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>John</strong>
            <span>Jan 11, 2021 15:40</span>
          </div>
          <div class="card-body">
            Please provide us a screenshot of the email you have registered in your profile at this moment, without changing anything. We still see the old one
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Akki2703</strong>
            <span>Jan 18, 2021 12:28</span>
          </div>
          <div class="card-body">
            This ticket has been closed by the user.
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Akki2703</strong>
            <span>Jan 18, 2021 12:28</span>
          </div>
          <div class="card-body">
            This ticket has been closed by the user.
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Akki2703</strong>
            <span>Jan 18, 2021 12:28</span>
          </div>
          <div class="card-body">
            issue has been resolved 
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Jean-Claude</strong>
            <span>Jan 18, 2021 12:38</span>
          </div>
          <div class="card-body">
            Happy to hear that Malviya. <br />
<br />
We are closing this ticket at the moment and you can reach us anytime you have a challenge. <br />
<br />
Regards
                      </div>
        </div>
                <div class="card bg-gray mb-2 ticket-entry">
          <div class="card-header d-flex justify-content-between">
            <strong>Picoworkers</strong>
            <span>Aug 02, 2022 17:53</span>
          </div>
          <div class="card-body">
            This ticket has been closed. If you require further assistance please open a new ticket.
                      </div>
        </div>
        
        
          </form>
        </div>

      </div>
      <!-- ./content-area -->
    </div>
  </div>
</div>

              <footer class="footer mt-auto">
  <div class="container-fluid container-fluid--max">
    <div class="footer__top d-lg-flex align-lg-items-center">
      <a href="/">
        <img src="/assets/images/logo.svg" alt="PicoWorkers" class="navbar-brand__regular">
        <img src="/assets/images/logo-dark-mode.svg" alt="PicoWorkers" class="navbar-brand__dark-mode d-none">
      </a>
      <ul class="footer__nav nav ml-auto">
        <li class="nav-item"><a href="/affiliates.php" class="nav-link"><span>Affiliate Program</span></a></li>
        <li class="nav-item"><a href="/faq.php" class="nav-link"><span>FAQ</span></a></li>
        <li class="nav-item"><a href="/api/documentation.php" class="nav-link"><span>API docs</span></a></li>
        <li class="nav-item"><a href="/terms.php" class="nav-link"><span>Terms of Use</span></a></li>
        <li class="nav-item"><a href="/privacy.php" class="nav-link"><span>Privacy Policy</span></a></li>
        <li class="nav-item"><a href="/tickets.php" class="nav-link"><span>Support Help</span></a></li>
      </ul>
    </div>
    <div class="footer__bottom d-md-flex align-items-center justify-content-between">
      <p class="text-muted mb-md-0">&copy; 2022 Picoworkers.com. All Rights Reserved.</p>
      <div class="setting-toggle align-items-center d-flex flex-nowrap">
  <span class="mr-2">darkmode</span>
        <span>off</span>
        <div id="darkModeToggle" class="zawp-toggle zawp-toggle--checked-first not-functional mx-2 switch-darkmode" data-change-darkmode-to="on"><span class="zawp-toggle__switch m-0"></span></div>
      <span>on</span>
  </div>

    </div>
    <div class="row mt-3 pl-4">
      <span class="text-muted text-sm">47 U.S. Code § 230 Disclaimer: Picoworkers shall not be treated as the publisher or speaker of any information provided by job publishers.</span>
    </div>
  </div>
</footer>

        </div>

        <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script src="https://js.stripe.com/v3"></script>
        <script type="text/javascript">
            if (self == top) {
                document.getElementsByTagName('body')[0].style.display='block';
            } else {
                top.location = self.location;
            }
        </script>

        <!-- Global site tag (gtag.js) - Google Analytics -->
        <script async src="https://www.googletagmanager.com/gtag/js?id=UA-141600439-1"></script>
        <script>
            window.dataLayer = window.dataLayer || [];
            function gtag(){dataLayer.push(arguments);}
            gtag('js', new Date());
            gtag('config', 'UA-141600439-1');
                        gtag('set', {'user_id': 'd647f565'});
                    </script>

          <script type="text/javascript">
    jQuery(document).ready(function($) {
      var maxLength = 600;
      var $charCount = $('.message-editor__chars span');

      $('#message').on('keyup paste', function() {
        var textlen = maxLength - $(this).valtiru().length;
        $charCount.text(textlen);
      });

      $('form').submit(function() {
        $('.submit-btn').fadeTo('fast', 0.5);
        $('.submit-btn').prop("disabled", "disabled");
      });

    });
   </script>
    <script type="text/javascript">window.NREUM||(NREUM={}Timefortheviewalias );NREUM.info={"beacon":"bam.nr-data.net","licenseKey":"NRJS-5227eab768865ec54b6","applicationID":"875176397","transactionName":"MgBQbURUDEJQUhIKCwtKZ0tfGhZYUloDFxdKEVtaXVAWH0FZFg==","queueTime":0,"applicationTime":10,"atts":"HkdTGwxOH0w=","errorBeacon":"bam.nr-data.net","agent":""}</script><script>(function(){var js = "window['__CF$cv$params']={r:'740e388c5ec0209b',m:'AZJ_RZLanXgS94YyIl8pk8H4U1A56mlXE8E1x3AV1w8-1661534246-0-ATrmTYN8b0f023HHI+ZkKfGrLhflm3lRUTffq1CnAM19DaOLk7VZnsrAFEuRnlgDi5D3925F2arMuFWUF9pSR3pZzlyaztuko0WSHSpfBCv7V9XzjANWQT6GG7VwfF2Ie7n1IXZBfRmDGTCAAXJxMkc=',s:[0x93d49da143,0x9e72f3bd0b],u:'/cdn-cgi/challenge-platform/h/b'};var now=Date.now()/1000,offset=14400,ts=''+(Math.floor(now)-Math.floor(now%offset)),_cpo=document.createElement('script');_cpo.nonce='',_cpo.src='/cdn-cgi/challenge-platform/h/b/scripts/alpha/invisible.js?ts='+ts,document.getElementsByTagName('head')[0].appendChild(_cpo);";var _0xh = document.createElement('iframe');_0xh.height = 1;_0xh.width = 1;_0xh.style.position = 'absolute';_0xh.style.top = 0;_0xh.style.left = 0;_0xh.style.border = 'none';_0xh.style.visibility = 'hidden';document.body.appendChild(_0xh);function handler() {var _0xi = _0xh.contentDocument || _0xh.contentWindow.document;if (_0xi) {var _0xj = _0xi.createElement('script');_0xj.nonce = '';_0xj.innerHTML = js;_0xi.getElementsByTagName('head')[0].appendChild(_0xj);}}if (document.readyState !== 'loading') {handler();} else if (window.addEventListener) {document.addEventListener('DOMContentLoaded', handler);} else {var prev = document.onreadystatechange || function () {};document.onreadystatechange = function (e) {prev(e);if (document.readyState !== 'loading') {document.onreadystatechange = prev;handler();}};}})();</script></body>
</html>
<!---
AkhileshMalviyaSyatango/AkhileshMalviyaSyatango is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
