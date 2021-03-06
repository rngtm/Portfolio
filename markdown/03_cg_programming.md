# CG Programming
CGプログラミング系のアウトプットをまとめていきます。

## GLSLレイマーチング
GLSLのレイマーチングを使用した作品はNEORTにまとめています。<br>
https://neort.io/Y2hWnzYpeUhPFLWEAZImqMboQI53 <br>
<br>

<table>
<tr>
    <td>
    シュリックの近似を利用して、金の延べ棒をレンダリングしたものです。<br>
    <iframe height="315" style="max-width: 560px; width: 100%; overflow:hidden; display:block;" src="https://neort.io/embed/butoc6k3p9f7gigec0qg?autoStart=false&quality=1&info=false" frameborder="0" sandbox="allow-forms allow-modals allow-pointer-lock allow-popups allow-same-origin allow-scripts" allow="geolocation; microphone; camera; midi; vr" allowfullscreen="true" allowtransparency="true"></iframe>
    </td>
    <td>
    シュリックの近似を利用して、水の反射・屈折を描画したものです。<br>
    <iframe height="315" style="max-width: 560px; width: 100%; overflow:hidden; display:block;" src="https://neort.io/embed/buo8u4s3p9f7gigeamng?autoStart=true&quality=1&info=false" frameborder="0" sandbox="allow-forms allow-modals allow-pointer-lock allow-popups allow-same-origin allow-scripts" allow="geolocation; microphone; camera; midi; vr" allowfullscreen="true" allowtransparency="true"></iframe>
    </td>
</tr>
<tr>
    <td>
    光の屈折を使用した水の表現です。<br>
    <img src = "../gif/raymarch/8_water_refraction.gif">
    </td>gitb
    <td>
    セルラーノイズを利用した水中表現です。<br>
    <a href="https://developer.download.nvidia.com/books/HTML/gpugems/gpugems_ch02.html">GPU Gems</a>を参考にして、コースティクスを実装しました。<br>
    <img src = "../gif/raymarch/7_voronoi_caustics.gif">
    </td>
</tr>
<tr>
    <td>
    高度hでのフォグ密度を1 - h / H とおき、<br>Rayが通過するフォグを積分したものを描画しています<br>
    <img src = "../gif/raymarch/05_height_fog.gif">
    </td>
    <td>
     <a href = "https://developer.nvidia.com/gpugems/gpugems2/part-ii-shading-lighting-and-shadows/chapter-16-accurate-atmospheric-scattering"> 
    GPU Gemsの大気散乱
    </a>を利用して、<br>フォグに映りこむ影を描画してみました。<br>
    <img src = "../gif/raymarch/6_fog_scatter.gif">
    </td>
</tr>
<tr>
    <td>    
    影のレンダリングを学びながら作成した作品です<br>
    <img src = "../gif/raymarch/01_shadow.gif">
    </td>
    <td> 
    光の屈折・反射の実装を学びつつ作成した作品です<br>
    <img src = "../gif/raymarch/03_lens_chromatic_abberation.gif">
    </td>
</tr>
<tr>
    <td>    
    Bling-Phonnの反射モデルを利用した作品です<br>
    <img src = "../gif/raymarch/04_sunset.gif">
    </td>
    <td>
    <a href = "https://developer.nvidia.com/gpugems/gpugems2/part-ii-shading-lighting-and-shadows/chapter-16-accurate-atmospheric-scattering"> 
    GPU Gemsの大気散乱
    </a>を利用した作品です<br>
    <img src = "../gif/raymarch/02_bamboo.gif"> 
    </td>
</tr>
</table>



