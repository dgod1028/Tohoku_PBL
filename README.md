# JupyterLab Desktopのインストール

JupyterLab Desktopは修正BSDライセンスで公開している**オープンソース・ソフトウェア**です。

## １．インストール

Jupyter Lab Desktopの[Github](https://github.com/jupyterlab/jupyterlab-desktop?tab=readme-ov-file)のページからダウンロードが可能です。

お使いのシステムに応じてダウンロードしてください。

<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1O-jadsULaZ8uW4vrM4fMLDYacXYOMqVw', width='50%'>
</div>

インストール後は、Windowsを例として、利用方法を紹介します。

## 2. 起動

インストール完了後、スタートメニューから`JupyterLab`を入力することで、アプリを検索し、起動できます。
ショートカットで保存しておくと、次回からは簡単に起動できます。

<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1O1m3IVN7xfPhzswDY3eejFJJc1cCXFV9', width='50%'>
</div>

## 3. 初期設定

１．もし使用中のパソコンにpythonが入っていない状態であれば、最初にpythonの環境を整える必要があります。
最初の起動画面で、下記の図で表示された`New Notebook`を選択します。

<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1ObolJz647uxJGUj3crGXhqZMRJasgMJ3', width='50%'>
</div>

２．設定画面に移動

続いて、下記の画面になると思いますが、図で示した通りに順番で設定画面に移動します。

<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1OetPeNhNWNdBXDjgh9dONfcMuDat1jZj', width='50%'>
</div>

３．python環境(Jupyter Server)のインストール

下記の画面に移動して、`Install`をクリックします。少し時間がかかりますが、インストールの完了を待ちます。
<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1Omtyl-ljxegJoe7B2gRwgzoet_7Y3W_a', width='50%'>
</div>

完了したら、下記の画面で、`Bundled Python environment`を選択した後、JupyterLabを再起動します。

<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1OLHKia4pVcC3x1Rk2vPp7clF-C5RDeKF', width='50%'>
</div>

## ４．日本語化

JupyterLab Desktopは、日本語に対応していますが、マニュアルでインストールする必要があります。

１．Jupyterlabを起動し、今度は`New Session`を選択します。

<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1OpbJXfPLeQsEK2_UdKfDr6e24lhFw3dN', width='50%'>
</div>

２．ランチャーの画面で、ターミナルを起動します。pythonのモジュールをインストールする際も、こちらを利用します。

<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1OqLbcFwmRWZpV1D0dkmtkqEQQ-7W9hw8', width='50%'>
</div>


３．ターミナルを起動した後、`pip install jupyterlab-language-pack-ja-JP`を入力し、実行します。これで日本語化パッチがインストールされますが、インストールが終わったら、一度JupyterLabを再起動する必要があります。

<div aligh='center'>
<img src='https://drive.google.com/uc?export=view&id=1OumsKYWe3cx8pndX7fmfjtKzvSQRB_9D', width='50%'>
</div>

４．再起動後、`New Notebook`を開き、下記のように`Settings`->`Language`->`Japanese`を選ぶことで、メニュー画面が日本語化されます。

![08](https://github.com/dgod1028/Tohoku_PBL/assets/16339858/4faa2786-9974-453d-8706-92cd7e1ad681)

## ５．最終確認

`New Notebook`を開き、コードを実行して、python環境がちゃんとインストールされていることを確認します。

![11](https://github.com/dgod1028/Tohoku_PBL/assets/16339858/74ded377-3044-4a3a-8716-d3757e8cdd9d | width=50)


- (オプション）左のファイルブラウザで、好きなフォルダやファイル作成が可能です。

![10](https://github.com/dgod1028/Tohoku_PBL/assets/16339858/4e7df92f-a51f-41fc-9a5b-5a249b3e9cb2)
