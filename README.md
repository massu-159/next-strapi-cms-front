# next-strapi-cms-front

アウトプットとして、Strapi を使った CMS アプリケーションのフロント作成。

フロントは Next.js (SSG)

サーバーサイドは CMS を利用。[Strapi](https://strapi.io/)

[Postman](https://www.postman.com/)を使って CRUD テスト。

food テーブル

```
food: {
  id,
  attributes: {
    foodName,
    description,
    price
  }
}
```

url はこちら
https://github.com/massu-159/next-strapi-cms-front

## 目次

1. 環境構築
2. アプリケーションの仕様

## 1. 環境構築

### 1-1. ライブラリ インストール

```
npm install

または

yarn
```

### 1-2. アプリケーション実行

```
npm run dev

または

yarn dev
```

## 2. アプリケーションの仕様

### 2-1. 仕様

- foodデータ
  - foodデータ一覧表示

### 2-2. 構成技術

- axios : 1.1.3
- next : 13.0.3
- react : 18.2.0
- react-dom : 18.2.0
