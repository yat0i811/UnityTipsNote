# ゲーム中にBGMを流す方法

1. BGMに使う音声ファイルをUnityに取り込む(フォルダからプロジェクトへドラッグ&ドロップ)<br>

1. BGMをアタッチするためのゲームオブジェクトを作成する
    - Hierarchyで右クリック ➡ CreateEmpty ➡ オブジェクトを作成<br>

1. 作成したオブジェクトをクリックし、Inspector内のAdd ComponentからAudio > Audio Sourceを選択

1. AudioClipに流したい曲のファイルをドラッグ＆ドロップ


※(Mute Audioがオン(白っぽく)になってると以上の動作をしても聞こえないよ)


[参考サイト](https://xr-hub.com/archives/18550)<br>
[公式ドキュメント](https://docs.unity3d.com/ja/2020.2/Manual/class-AudioSource.html)<br>
