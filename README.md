
:root {
--tombol-bg: rgba(0, 0, 0, .3); 
--tombol-teks: #fff;
--tombol-bingkai: #fff;
--bingkai: 8px;
--bingkai-kiri: 1.3px solid var(--tombol-bingkai);
--bingkai-kanan: 1.3px solid var(--tombol-bingkai);
--gaya-font: 'Shippori Antique', sans-serif;
--gaya-font2: 'Dancing Script', sans-serif;
}
@keyframes fanim {0% {background-position: 0% 0%;}25% {background-position: 100% 100%;} 50% {background-position: 0% 100%;} 75% {background-position: 50% 50%;} 100% {background-position: 0% 0%;}}
body{background-color:#000;font-family:var(--gaya-font);padding: 20px 25px;-webkit-user-select: none; -ms-user-select: none; user-select: none;} a{text-decoration:none;}
body::before{content:"\00A9  Whyskaa_ ";color:white;opacity:.05;font-size:10px;position:fixed;bottom:25px;right:25px;z-index:2}
#bodyblur{opacity:0;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);transition:all 1s ease;} 
#wallpaper{width:100%;height:100%;transform: scale(2);transition:all 1.3s ease;}
#beneranblur{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);-webkit-backdrop-filter:blur(0px); backdrop-filter:blur(0px);transition:all 3s ease;}

@keyframes jj{0%  {transform: scale(1.1);} 50% {transform: scale(1.2);} 100% {transform: scale(1.1);}}
@keyframes rts{from {transform:scale(.1);} to {transform:scale(1);}}
@keyframes rto{from {transform:scale(1);} to {transform:scale(1.1);}}
@keyframes aniopa{0% {transform: scale(1);} 50% {transform: scale(.75);} 100% {transform: scale(1);}}
@keyframes rtf{from {transform: rotate(0deg);} to {transform: rotate(360deg);}} @keyframes rt{from {transform: scale(.9);/* transform: rotate(-5deg); */} to {transform: scale(1);/* transform: rotate(5deg); */}}
@keyframes kont{0%  {left:-1px; top:-3px;} 50% {left:1px; top:3px;} 100% {left:-1px; top:-3px;}}

blockquote{position:absolute;opacity:0;visibility:hidden;margin-top:100px;background:var(--tombol-bg);border-radius:18px 0 18px 0;box-shadow: rgba(255,255,255, 0.3) 0px 7px 29px 0px;transform: scale(.1);transition:all 1s ease;margin-top:120px;margin-left:0;margin-right:0;color:var(--tombol-teks);text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);}
blockquote{width:400px;text-align:center;line-height:1.3em;padding:20px 25px 20px 25px;}
blockquote::before{content:attr(data-text);opacity:.7;font-family: sans-serif;position:absolute;left:8px;top:8px;min-width:15px;font-size:16px;text-align:center}
blockquote::after{content: "";position: absolute;border: 1px solid #fff;border-radius:18px 0 18px 0;top: -8px;bottom: -8px;left: -8px;right: -8px;}
blockquote p{font-size:16px;font-weight:700;line-height:1.4em;transition:all .5s ease;}
blockquote > #kalimatb, blockquote > .sty2{font-size:15px;font-weight:400}
blockquote > #pesan4{margin-top:25px} blockquote > .sty2{line-height:1em;}
blockquote p:not(#opsL, #kalimat, #kalimatb, .sty2){display:none;}
blockquote > #opsL{text-align:right;font-size:11px;font-weight:400;line-height:0;margin-top:24px;color:white;opacity:0;transition:all .2s ease;}

#waktu{display:none}
#kado1, #kado2, #kado3{font-size:16px;font-weight:400;}
#kalimatAkhir{transform:scale(.1);}
#kado1{position:absolute;opacity:0}
#kalove{font-size:25px;line-height:0;}
.kolombar .inibar{position:absolute;opacity:0;visibility:hidden;background-color:#fff;height:5px;width:100%}

#Tombol{position:relative;opacity:0;margin:0;display:flex;align-items:left;list-style:none;transform: scale(.1);transition:all 1s ease;}
#Tombol a{cursor:pointer;display:inline-flex;align-items:center; margin:0;margin:12px 0 12px 0;transition:all .2s ease;padding:10px;outline:0;border: 1px solid #fff;border-radius:18px;line-height:15px;background:rgba(0,0,0,.5);color:var(--tombol-teks);font-size:12px;font-weight:700;white-space:nowrap;overflow:hidden;box-shadow: rgba(255,255,255, 0.3) 0px 7px 29px 0px;z-index:1} 
#Bn{margin:12px 0 12px 12px !important;}
#Bn2{position:absolute;opacity:0;width:0}

#Content{animation-name:none;animation-duration: 3s;animation-iteration-count: infinite;position:relative;opacity:0;margin-top:50px;width:100%;height:180px;transition:all .7s ease;}
#Content > *{display:flex;align-items:center;text-align:center;justify-content:center;margin-top:1px;}
.kumpulanstiker > img{display:none;background: rgba(255, 255, 255, 0.2);box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(5px);-webkit-backdrop-filter: blur(5px);border: 1px solid rgba(255, 255, 255, 0.3);border-radius: 50%;padding:10px;width:100px;height:100px;margin:20px 0;}
#fotostiker{opacity:.1;transition:all 1.2s ease;transform: scale(.1);}
.halo{font-size:18px !important;position:relative;margin:15px 0 20px 0} 
.halo.sty2{font-family:var(--gaya-font2);font-size:24px !important;margin-top:20px !important;}
.halo.sty3{position:absolute !important;font-size:14px !important;font-weight:400 !important;margin:30px 20px !important;}
#kalimatbawah{position: absolute;opacity:0;transform: scale(.3);margin:50px 0;font-family:var(--gaya-font2);font-size:20px;font-weight:700;color:white;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);transition:all .5s ease;}
#tanggal{position: absolute;opacity:0;transform: scale(.3);transition:all .5s ease;}

#fotolove img{transition:all .5s ease;width:75px;height:75px;padding:0;background:none}
#kadoIn img{display:inline-flex;background:none;width:130px;height:130px;transition:all .3s ease;} 
#ket, .halo{text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);font-size:17px;font-weight:700;color:white}
#ket{margin-top:25px !important;font-weight:400;}
#kadoIn img:hover{transform:scale(.9);}

#kolombaru{position:absolute;opacity:0;display:flex;transform:scale(.1);transition:all 1s ease;align-items:center;text-align:center;justify-content:center;z-index:1;}
#kolombaru > li{margin:8px;padding:0;list-style-type: none;}
#kolombaru li{opacity:.8;display:flex;font-size:30px}
#kolombaru li:hover{opacity:.5;transform: scale(1.15);transition:all .3s ease;}

.kolomrange{padding:0;background:none;position:relative;z-index:1;display:none;transition:all 1s ease;align-items:center;}
.kolomrange .inirange{width:100%;height:40px;margin-right:15px;display:flex;align-items:center;text-align:center;justify-content:center;}
.kolomrange .inirange input{height:10px;width:100%;-webkit-appearance:none;outline:none;background:#f2f2f2;border-radius:25px;box-shadow:inset 0px 0px 4px rgba(0,0,0,0.2);}
.kolomrange .inirange input::-webkit-slider-thumb{-webkit-appearance:none;appearance:none;width:20px;height:20px;border-radius:50%;border:3px solid #006FFF;background:white;transition:all .2s ease;}
.kolomrange .inirange input::-webkit-slider-thumb:hover{border:5px solid #006FFF;}
.kolomrange .inivalue{color:white;font-size:20px}

.swal2-modal > *{font-size:16px;}
.swal2-title{line-height:1.3em;font-size:17px;text-align:center;padding:15px 30px 0 30px;}
.swal2-timer-progress-bar-container > *{opacity:.7;background:#00B6FF;margin:0 2px}
.swal2-modal{background:#EAEAEA;box-shadow: 0 4px 30px rgba(255,255,255, 0.3);backdrop-filter: blur(2px);-webkit-backdrop-filter: blur(2px);border: 1px solid rgba(255, 255, 255, 0.3);border-radius: 8px;max-width:330px;top:-60px;}
.swal2-styled.swal2-confirm, .swal2-styled.swal2-cancel{position: relative;background-color: #4839eb;color: #fff;border-radius:18px;z-index: 1;transition: all 0.2s;}

.fa-snowflake {opacity:.3;color:white;font-size: 20px;position: absolute;animation:  heartMove linear 1;top: -10vh;z-index: 0;}
@keyframes heartMove {0%{transform: translateY(-10vh) ;} 100%{transform: translateY(100vh) ;}}
.sembunyi, #pesanditolak > *, #kado2, #kado3{display:none !important}
