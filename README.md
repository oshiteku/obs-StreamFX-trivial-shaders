# obs-StreamFX-trivial-shaders

Read in [**English**](README_en.md).

obs-StreamFX-trivial-shaders は [StreamFX](https://github.com/Xaymar/obs-StreamFX) 用のシェーダ集です。

## シェーダ一覧

|Shader|Type|Description|
-------|----|------------
|[outline](filter/outline/)|filter|非透過領域の周りに枠線を描画します。縁取り効果とも呼ばれます。参考動画: https://youtu.be/hZGJk9RVzZs|
|[pixel-outline](filter/outline/)|filter|解像度の低いoutlineを描画します。ピクセルアートのような縁取り効果です。|
|[transparent-gradient](filter/transparent-gradient/)|filter|徐々に透明になっていくグラデーション透過を適用します。|
|[border-radius](filter/border-radius/)|filter|境界の角を丸めます。|
|[squircle](filter/border-radius/)|filter|[Squircle](https://en.wikipedia.org/wiki/Squircle)によってソースをくり抜きます。|
|[smooth-border-radius](filter/border-radius/)|filter|Squircleによって滑らかに境界の角を丸めます。|
|[drop-shadow](filter/drop-shadow/)|filter|ドロップシャドウを適用します。|
|[drop-shadow-auto-padding](filter/drop-shadow/)|filter|ドロップシャドウを適用します。加えて、描画領域に収まるように自動的に縮小を行います。|
|[blink-pwm](filter/blink/)|filter|点滅エフェクトを適用します。|
