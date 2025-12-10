# Timer Control App

## 📌 概要
アプリ全体のタイマー状態を Context と Reducer を使って管理する TypeScript 実践アプリです。
コンポーネント間のデータ共有、forwardRef、ジェネリック型など、より高度な型付けパターンを学ぶことを目的としています。

## 🛠️ 技術スタック
- TypeScript
- React
- Context API
- useReducer
- forwardRef / ComponentPropsWithoutRef
- useImperativeHandle

## 🎯 主な機能
- タイマーの追加・開始・一時停止
- 複数タイマーの並行管理
- ボタンコンポーネントの汎用化（button / a の動的切り替え）
- タイマー表示コンポーネントの制御（開始 / 停止）

## 💡 学習ポイント
- Context と Reducer の組み合わせによる状態管理と、その型定義
- `createContext` のジェネリック型設定（値・関数・初期値の型安全化）
- `ComponentPropsWithoutRef` を使った汎用コンポーネント設計
- `forwardRef` で親コンポーネントから ref を受け取る型付け
- ジェネリックを使ったパラメータ型・戻り値型の設計
- `useImperativeHandle` を利用したカスタムメソッド公開とその型定義
- コンテナパターンでの「受け取る要素に応じた型の制御」
