# GPUPTrail
シェーダとカスタムレンダーテクスチャによって構成されたトレイルレンダラーです。

C#スクリプトを一切使用していない構成になっています。

VRでの使用を想定し、視点が回転しても大きく変化しないようにビルボードを行っています。

inputmaterialからトレイル群の挙動に関するパラメーター操作が、GpuPtrailrenderermaterialから見た目に関するパラメーター操作ができます。