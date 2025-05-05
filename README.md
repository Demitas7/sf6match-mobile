# SF6match-mobile

SF6match-mobileは、ストリートファイター6（SF6）のプレイヤー向けモバイルアプリケーションです。プレイヤーの試合データを分析し、パフォーマンス向上をサポートします。

## 機能

- プレイヤープロフィールの表示
- 試合履歴の確認
- 統計データの分析
- パフォーマンス指標の可視化

## 技術スタック

- React Native
- TypeScript
- Redux Toolkit
- React Navigation
- Jest (テスト)

## 開発環境のセットアップ

1. 必要なツールのインストール
   - Node.js (v18以上)
   - Xcode (iOS開発用)
   - Android Studio (Android開発用)
   - CocoaPods (iOS依存関係管理用)

2. プロジェクトのクローン
   ```bash
   git clone https://github.com/your-username/sf6match-mobile.git
   cd sf6match-mobile
   ```

3. 依存関係のインストール
   ```bash
   npm install
   ```

4. iOS依存関係のインストール
   ```bash
   cd ios
   pod install
   cd ..
   ```

5. アプリケーションの起動
   ```bash
   # iOS
   npm run ios
   
   # Android
   npm run android
   ```

## プロジェクト構造

```
src/
├── components/     # 再利用可能なUIコンポーネント
├── screens/        # 画面コンポーネント
├── navigation/     # ナビゲーション設定
├── store/         # Reduxストア設定
├── services/      # API通信
├── utils/         # ユーティリティ関数
└── types/         # TypeScript型定義
```

## ライセンス

MIT License 