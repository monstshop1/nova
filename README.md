<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ちーと用PC設定手順</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 p-8">
    <div class="max-w-4xl mx-auto bg-white p-6 rounded-lg shadow-lg">
        <!-- 注意書き -->
        <p class="mb-4">
            &#x1f64b; ちーとを導入する際にまず必要なやる事リストを記載しています。<br>
            初心者の方も多いと思うので、動画付きで丁寧に案内します。。<br>
            クリーンインストールした後などは、このガイドを見ればPCが一発でCが使える環境になります。
        </p>

        <!-- グーグルクロームをインストール -->
        <h2 class="text-xl font-semibold mb-4">グーグルクロームをインストール</h2>
        <p class="mb-4">
            <a href="https://www.google.com/intl/ja_jp/chrome/" class="text-blue-500 underline">https://www.google.com/intl/ja_jp/chrome/</a><br>
            edgeから該当ページをダウンロードしようとすると、不審なアクセスなんたらでブロックされて面倒なのでクロームを入れましょう。<br>
			後書くか迷ったのですが、解凍する際に7zipとかwinrarとかは好みで入れてください。
        </p>

        <!-- アプリとブラウザーコントロール設定の説明 -->
        <div class="mb-8">
            <h3 class="text-lg font-semibold mb-2">アプリとブラウザーコントロール</h3>
            <img src="https://i.imgur.com/fFthVSE.png" alt="アプリとブラウザーコントロール" 
     class="w-full max-w-[500px] border mb-4">


            <ul class="list-disc pl-5 space-y-2">
                <li>ファイルのダウンロードをする際に、これがオンだと一々警告が出てうるさいので上記画像のように設定推奨です</li>
            </ul>
        </div>

        <!-- 手順リスト -->
        <div class="mb-8">
            <h2 class="text-xl font-semibold mb-4">&#x1F4DD; 手順リスト</h2>

            <!-- ①ユーザーアカウント制御を無効化する -->
            <div class="mb-6">
                <h3 class="font-semibold mb-2">①ユーザーアカウント制御を無効化する</h3>
                <p class="mb-2">
                    理由: ダウンロード時に一々警告のポップアップが出て邪魔だったり、Cは基本管理者権限で動くのでその際に邪魔な作用をしたりするのでまず無効にしましょう。下の動画参考にしてください
                </p>
                <p class="text-blue-500">
                    <a href="https://youtu.be/dNqGMXTlZ48" target="_blank">https://youtu.be/dNqGMXTlZ48</a>
                </p>
            </div>

            <!-- ②ウイルス対策を切る、ウイルスソフトをアンインストールする -->
            <div class="mb-6">
                <h3 class="font-semibold mb-2">②ウイルス対策を切る、ウイルスソフトをアンインストールする</h3>
                <p class="mb-2">
                    理由: ３～で導入するソフトやC本体がそもそも、ウイルスと見做されて消される為 必須です。下記動画を参考にしてください。
                </p>
                <p class="text-blue-500">
                    <a href="https://youtu.be/U9juXLI0rHA" target="_blank">https://youtu.be/U9juXLI0rHA</a>
                </p>
            </div>

            <!-- ③ディフェンダーコントロールを入れて実行 -->
            <div class="mb-6">
                <h3 class="font-semibold mb-2">③ディフェンダーコントロールを入れて実行</h3>
                <p class="mb-2">
                    理由: 🧀はPCの脆弱性をついて 導入するので、WINDOWS側からしたら当然ウイルス扱いをされている
                </p>
                <p class="mb-2">再起動したら仕様上ウイルス対策がまたオンになっちゃうので、これを使うと毎回オフにできます。</p>
                <p class="mb-2">参考動画は下記から※ダウンロードパスは【sordum】です。</p>
                <p class="text-blue-500">
                    <a href="https://youtu.be/FWiXNAjVpbo" target="_blank">https://youtu.be/FWiXNAjVpbo</a>
                </p>
            </div>

            <!-- ④WUBを入れる -->
            <div class="mb-6">
                <h3 class="font-semibold mb-2">④WUBを入れる</h3>
                <p class="mb-2">
                    ウィンドウズの更新が定期的に入ると、ウイルス対策アップデートがあったりして アプリが動作しなくなったりする可能性あります。
					<p class="mb-2">手動で更新を停止するで停止させても良いですが、面倒くさい人は入れてください。</p>
                </p>
                <p class="text-blue-500">
                    <a href="https://youtu.be/L_f1STsnT6M" target="_blank">https://youtu.be/L_f1STsnT6M</a>
					
                </p>
           
    </div><!-- ⑤その他必要項目のダウンロード -->
<div class="mb-6">
    <h3 class="font-semibold mb-2">⑤その他必要項目のダウンロード</h3>
    <p class="mb-2">
	下記を２つをダウンロードして実行してください。<br>
        <a href="https://www.microsoft.com/ja-jp/download/details.aspx?id=35" class="text-blue-500 underline" target="_blank">
            https://www.microsoft.com/ja-jp/download/details.aspx?id=35
        </a>
    </p>
    <p class="mb-2">
        <a href="https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/" class="text-blue-500 underline" target="_blank">
            https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/
        </a>
	</p>
	上から、dxwebsetup.exeはそのまま実行⇒同意、
	</p>
	Visual C++ Redistributable Runtimes All-in-Oneは左側にあるdownloadをクリック
	</p>
	⇒左上にcloset to youという国名が表記されているのでダウンロードしてインストーラーを実行です。
	</p>
	わかりにくいので動画にしました。
    </p>
	                <p class="text-blue-500">
                    <a href="https://youtu.be/jY_EfDdZS-U" target="_blank">https://youtu.be/jY_EfDdZS-U</a>
</div>
            <!-- ⑦その他ダウンロード品目 -->
            <div class="mb-6">
                <h3 class="font-semibold mb-2">⑦その他ダウンロード品目</h3>
                <p class="mb-2">
                    ディスコードとかGeforce Experienceとか必要なものを入れてください。
					<p class="mb-2">※クリーンインストール後にgeforce入れないと、valo起動しなかったりするので要注意</p>	
                </p>

</body>
</html>
