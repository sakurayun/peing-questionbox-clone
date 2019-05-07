# peing-質問箱-のクローン(OSS)

みなさん[peing-質問箱-](https://peing.net/)をご存知ですか?twitterで2017年ごろから流行っている匿名で質問ができるwebサービスのことです。このサービスは個人開発をしているせせり氏が開発したサービスで公開１ヶ月で1億アクセスに達したそうです。

匿名で質問できるという機能はとても面白いと思いました。なのでこれをオープンソース化して、もっといろんな機能をつけていきたいと考えています。

___

### デプロイ deploy
誰でもカンタンにデプロイできるようにしましたので是非みなさんもお使いください。
まずはgitからファイルをダウンロードしてください。
``` git clone git@github.com:seiyatakahashi/peing-questionbox-clone.git ```

ダウンロードができたらダウンロードしてきたフォルダに移動する
``` cd peing-questionbox-clone ```

herokuにログインをする
``` heroku login ```

heorku でプロジェクトを作成する
``` heroku create```


___

### 今後つけたい機能
##### 決済機能
質問したい人がお金を払って質問された人がお金をもらえる機能。
##### 複数のSNSログイン
現在twitterでのログインしかできなのでfacebookやlineなどを加えたいです。
##### ネイティブアプリ化
railsをapi化させて、iosやandroidのようなネイティブなアプリケーションを作りたいです。
