<div style="font-family: sans-serif;">

<h1 style="font-size: 2.2em; border-bottom: 2px solid #ddd; padding-bottom: 10px;">
  Real-time Object Detection Web App
</h1>

<p style="font-size: 1.1em; line-height: 1.6;">
  これは、Next.js と TensorFlow.js を使用して作成されたリアルタイム物体検出Webアプリケーションです。ブラウザ上でウェブカメラを使用し、リアルタイムで物体を認識して表示します。
</p>

<p style="font-size: 1.1em;">
  <strong>デモサイト:</strong> <a href="https://https-github-com-taru104-object-det.vercel.app/">https://https-github-com-taru104-object-det.vercel.app/</a>
</p>

<hr>

<h2 style="font-size: 1.8em; border-bottom: 1px solid #eee; padding-bottom: 8px;">
  主な機能
</h2>

<ul style="font-size: 1.1em; line-height: 1.7;">
  <li><strong>リアルタイム物体検出</strong>: ウェブカメラの映像からリアルタイムで物体を検出し、バウンディングボックス（囲み枠）とラベル、信頼度スコアを表示します。</li>
  <li><strong>Webカメラ対応</strong>: ユーザーの許可を得て、デバイスのカメラにアクセスし、ライブ映像を処理します。</li>
  <li><strong>クライアントサイド処理</strong>: TensorFlow.js を利用することで、サーバーに映像を送ることなく、すべてブラウザ上で機械学習モデルの読み込みと推論を実行します。</li>
</ul>

<h2 style="font-size: 1.8em; border-bottom: 1px solid #eee; padding-bottom: 8px;">
  使用技術
</h2>

<ul style="font-size: 1.1em; line-height: 1.7;">
  <li><strong>フレームワーク</strong>: Next.js (React)</li>
  <li><strong>言語</strong>: TypeScript</li>
  <li><strong>機械学習ライブラリ</strong>: TensorFlow.js (<code>@tensorflow/tfjs</code>)</li>
  <li><strong>物体検出モデル</strong>: COCO-SSD (<code>@tensorflow-models/coco-ssd</code>)</li>
  <li><strong>Webカメラ連携</strong>: <code>react-webcam</code></li>
  <li><strong>ホスティング</strong>: Vercel</li>
</ul>

<h2 style="font-size: 1.8em; border-bottom: 1px solid #eee; padding-bottom: 8px;">
  セットアップと実行方法
</h2>

<p style="font-size: 1.1em;">
  ローカル環境で開発サーバーを起動する手順は以下の通りです。
</p>

<ol style="font-size: 1.1em; line-height: 1.7;">
  <li>
    <strong>リポジトリをクローンする</strong>
    <br>
    <em>(注: `YOUR-REPO-NAME` の部分は、ご自身の正しいリポジトリ名に書き換えてください)</em>
<pre><code>git clone https://github.com/taru104/YOUR-REPO-NAME.git</code></pre>
  </li>
  <li>
    <strong>プロジェクトディレクトリに移動する</strong>
<pre><code>cd YOUR-REPO-NAME</code></pre>
  </li>
  <li>
    <strong>依存関係をインストールする</strong>
<pre><code>npm install</code></pre>
  </li>
  <li>
    <strong>開発サーバーを起動する</strong>
<pre><code>npm run dev</code></pre>
  </li>
</ol>

<p style="font-size: 1.1em;">
  ブラウザで <a href="http://localhost:3000">http://localhost:3000</a> を開き、カメラへのアクセスを許可するとアプリケーションが表示されます。
</p>

</div>
