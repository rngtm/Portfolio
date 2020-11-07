# CG Programming
CGプログラミング系のアウトプットをまとめていきます。

## GLSLレイマーチング
GLSLのレイマーチングを使用した作品はNEORTにまとめています。<br>
https://neort.io/Y2hWnzYpeUhPFLWEAZImqMboQI53 <br>
<br>

<table>
<tr>
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
