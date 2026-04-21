<!doctype html>
<html lang="de">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1" />
    <title>KI-Trends Bau 2026 · Fakten-Dashboard für das 3. Transformationsforum</title>
    <meta name="description" content="Konsolidiertes Fakten-Dashboard zu KI, Daten und BIM in der Baubranche: Datenschema-Fails, Kostenfalle, Produktivitätsschere, LLMs auf Baudokumenten, deutsche Fallstudien, Adoption, Data Literacy, CO₂. 55 Quellen, Stand 21.04.2026. Vorbereitet für den Impulsvortrag „Daten als Rohstoff der Transformation“ beim 3. Transformationsforum Bau in Heilbronn." />
    <meta name="theme-color" content="#0B1F22" />

    <!-- Open Graph -->
    <meta property="og:type" content="website" />
    <meta property="og:title" content="KI-Trends Bau 2026 · Fakten-Dashboard" />
    <meta property="og:description" content="Datenschema-Fails, 1,85 Bio. USD Kostenfalle, Produktivitätsschere, deutsche Fallstudien, BIM-Reife, Data Literacy, CO₂. 55 Quellen, Stand 21.04.2026." />
    <meta property="og:locale" content="de_DE" />
    <meta property="og:site_name" content="KI-Trends Bau 2026" />
    
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap"
      rel="stylesheet"
    />
    <script type="module" crossorigin src="./assets/index-XrhO8g2S.js"></script>
    <link rel="stylesheet" crossorigin href="./assets/index-HtGXAkof.css">
  </head>
  <body>
    <div id="root"></div>
  <script data-pplx-inline-edit>
(function(){
  if(window===window.top)return;
  function inlineAll(orig,clone){
    if(orig.nodeType!==1)return;
    try{
      var cs=getComputedStyle(orig);
      var t='';
      for(var i=0;i<cs.length;i++){t+=cs[i]+':'+cs.getPropertyValue(cs[i])+';';}
      clone.style.cssText=t;
    }catch(e){}
    var oc=orig.children,cc=clone.children;
    for(var j=0;j<oc.length&&j<cc.length;j++){inlineAll(oc[j],cc[j]);}
  }
  function stripExternal(clone){
    var imgs=clone.querySelectorAll('img');
    for(var i=0;i<imgs.length;i++){
      var s=imgs[i].getAttribute('src');
      if(s&&!s.startsWith('data:'))imgs[i].removeAttribute('src');
    }
    var all=clone.querySelectorAll('*');
    for(var i=0;i<all.length;i++){
      var st=all[i].style.cssText;
      if(st&&st.indexOf('url(')>=0){
        all[i].style.cssText=st.replace(/url\(["']?(?!data:)[^)"']*["']?\)/gi,'none');
      }
    }
  }
  var scrollRaf=0;
  function emitScroll(){
    scrollRaf=0;
    var x=window.scrollX||window.pageXOffset||0;
    var y=window.scrollY||window.pageYOffset||0;
    window.parent.postMessage({type:'INLINE_EDIT_SCROLL',scrollX:x,scrollY:y},'*');
  }
  window.addEventListener('scroll',function(){
    if(scrollRaf)return;
    scrollRaf=requestAnimationFrame(emitScroll);
  },{passive:true,capture:true});
  emitScroll();
  window.addEventListener('message',function(e){
    if(!e.data||e.data.type!=='INLINE_EDIT_CAPTURE_REQUEST')return;
    var scrollX=window.scrollX||window.pageXOffset||0;
    var scrollY=window.scrollY||window.pageYOffset||0;
    var w=window.innerWidth,h=window.innerHeight;
    try{
      var clone=document.documentElement.cloneNode(true);
      var rm=clone.querySelectorAll('script,link[rel="stylesheet"],style');
      for(var i=0;i<rm.length;i++){rm[i].remove();}
      inlineAll(document.documentElement,clone);
      stripExternal(clone);
      var html=new XMLSerializer().serializeToString(clone);
      var svg='<svg xmlns="http://www.w3.org/2000/svg" width="'+w+'" height="'+h+'">'
        +'<foreignObject width="100%" height="100%">'
        +'<div xmlns="http://www.w3.org/1999/xhtml" style="width:'+w+'px;height:'+h+'px;overflow:hidden">'
        +'<div style="transform:translate(-'+scrollX+'px,-'+scrollY+'px);transform-origin:top left">'
        +html+'</div></div></foreignObject></svg>';
      var svgUrl='data:image/svg+xml;charset=utf-8,'+encodeURIComponent(svg);
      var img=new Image();
      img.onload=function(){
        var c=document.createElement('canvas');c.width=w;c.height=h;
        c.getContext('2d').drawImage(img,0,0);
        window.parent.postMessage({type:'INLINE_EDIT_SCREENSHOT_RESULT',dataUrl:c.toDataURL('image/png'),scrollX:scrollX,scrollY:scrollY},'*');
      };
      img.onerror=function(){
        window.parent.postMessage({type:'INLINE_EDIT_SCREENSHOT_RESULT',dataUrl:null,scrollX:scrollX,scrollY:scrollY},'*');
      };
      img.src=svgUrl;
    }catch(err){
      window.parent.postMessage({type:'INLINE_EDIT_SCREENSHOT_RESULT',dataUrl:null,scrollX:scrollX,scrollY:scrollY},'*');
    }
  });
})();
</script></body>
</html>
