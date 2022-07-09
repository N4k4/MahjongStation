# MahjongStation

version:0.0.0

Author:Naka

## usage
now construction

## これは何？
 MahjongStation(以下、本ソフト)麻雀の思考CPUの対戦GUIにしたいと思っているプロジェクトです。

 ゼロから作っているため、途中で破綻する可能性が高いですが個人の制作物のため完成の保証および動作の保証は取れません。ご承知おきください。

 ## 実装予定の機能
- 思考エンジン4人による対戦
- 人間一人と思考エンジン4人による対戦
- ３人麻雀に対応
- 赤牌のオンオフ
- ３人麻雀における北牌の扱いの対応
    - 役牌扱い
    - ドら抜き

Mリーグや天鳳、雀魂など様々な麻雀ルールに対応できるように拡張性を高める実装を試みたいと思っています。

実装に伴って、思考エンジンと本ソフト間でデータのやり取りをするプロトコルの策定も行います。

## MJI プロトコル

本ソフトと思考エンジンのやりとりをするためにMahJongInterfaceプロトコルを策定した。[MJIプロトコルのドキュメント](./document/MJIProtocol.md)を参照のこと