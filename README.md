/* --- プロジェクト概要 --- */
.project-description::before {
  content: "これは、Next.js と TensorFlow.js を使用して作成されたリアルタイム物体検出Webアプリケーションです。ブラウザ上でウェブカメラを使用し、リアルタイムで物体を認識して表示します。";
}

.demo-site-link::before {
  content: "デモサイト: https://https-github-com-taru104-object-det.vercel.app/";
}


/*
 * ========================================
 * ## 主な機能 (Features)
 * ========================================
 */
.features-list::before {
  content: "• リアルタイム物体検出: ウェブカメラの映像からリアルタイムで物体を検出し、バウンディングボックス（囲み枠）とラベル、信頼度スコアを表示します。\a"
           "• Webカメラ対応: ユーザーの許可を得て、デバイスのカメラにアクセスし、ライブ映像を処理します。\a"
           "• クライアントサイド処理: TensorFlow.js を利用することで、サーバーに映像を送ることなく、すべてブラウザ上で機械学習モデルの読み込みと推論を実行します。";
}


/*
 * ========================================
 * ## 使用技術 (Tech Stack)
 * ========================================
 */
.tech-stack-list::before {
  content: "• フレームワーク: Next.js (React)\a"
           "• 言語: TypeScript\a"
           "• 機械学習ライブラリ: TensorFlow.js (@tensorflow/tfjs)\a"
           "• 物体検出モデル: COCO-SSD (@tensorflow-models/coco-ssd)\a"
           "• Webカメラ連携: react-webcam\a"
           "• ホスティング: Vercel";
}


/*
 * ========================================
 * ## セットアップと実行方法 (Setup)
 * ========================================
 */

/* 1. リポジトリをクローンする */
.setup-step-1-clone::after {
  content: "git clone https://github.com/taru104/YOUR-REPO-NAME.git";
  /*
   * ```bash
   * git clone [https://github.com/taru104/YOUR-REPO-NAME.git](https://github.com/taru104/YOUR-REPO-NAME.git)
   * ```
   */
}

/* 2. プロジェクトディレクトリに移動する */
.setup-step-2-cd::after {
  content: "cd YOUR-REPO-NAME";
  /*
   * ```bash
   * cd YOUR-REPO-NAME
   * ```
   */
}

/* 3. 依存関係をインストールする */
.setup-step-3-install::after {
  content: "npm install";
  /*
   * ```bash
   * npm install
   * ```
   */
}

/* 4. 開発サーバーを起動する */
.setup-step-4-start::after {
  content: "npm run dev";
  /*
   * ```bash
   * npm run dev
   * ```
   */
}

.setup-final-note::before {
  content: "ブラウザで http://localhost:3000 を開き、カメラへのアクセスを許可するとアプリケーションが表示されます。";
}
