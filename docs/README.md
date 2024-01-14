# 職務経歴書

## 基本情報

| key         | value                               |
| ----------- | ----------------------------------- |
| 氏名        | 稲井友亮（Inai Yusuke）             |
| 生年月日    | 1996/10/26                          |
| 居住地      | 東京都                              |
| 最終学歴    | 滋賀医科大学医学部医学科 中退       |
| Twitter     | https://twitter.com/yusuke_blog1026 |
| Qiita       | https://qiita.com/yusuke_blog1026   |
| Zenn        | https://zenn.dev/youliangdao        |
| SpeakerDeck | https://speakerdeck.com/youliangdao |

---

## 保有スキル・資格

- Next.js を用いたフロントエンド開発・設計
- TypeScript + React でのフロントエンド開発・設計（SPA 開発）
- React Testing Library + Jest + Storybook を用いたフロントエンドテスト設計
- Playwright を用いた E2E テストの作成
- フロントエンド開発基盤の整備（テスト環境、CI 構築など）
- Ruby on Rails でのサーバーサイド開発
- AWS ＋ Terraform を用いたインフラ基盤の作成
- スクラム開発
- ドキュメント作成
- テックブログ運営
- AWS クラウドプラクティショナー／LPIC1

## 技術スタック

### 言語

- TypeScript
- JavaScript
- Ruby

### フレームワーク・その他

- Next.js
- React
- Ruby on Rails
- Vite
- Docker
- Cloudflare

## 職務経歴書詳細

### 株式会社 COUNTERWORKS（2023/06〜現在）

商業施設向け SaaS である「Shopcounter Enterprise」の新規開発・保守運用を行ってきました。

主に UI / UX 設計や UI 実装（コンポーネント設計、複雑なフォーム実装など）、さらにはテスト設計やリリース作業などを担当していました。

得意としているフロントエンド開発の知見を活かして、フロントエンド基盤の改善や既存機能の改修をリード。開発初期は人の入れ替わりが激しく負債化しているコードが多数存在していたため、コンポーネント設計の指針を定めて、誰でも統一されたコードを書けるようにしました。さらに並行してテスト文化も根付いていなかったため、組織内で議論を重ね自らが旗振り役になり、Storybook などを導入してテストを積極的に書くよう工夫しました。

また組織文化作りとしてドキュメント力を活かし、テックブログ運営も行っておりました。私が配属されるまではテックブログを書く文化がありませんでしたが、アイデア出しや記事のテンプレートを用意することで、アドベントカレンダーを実施できるまでに至りました。

- プロジェクト規模：
  - 平均 5 人程度のチームでのスクラム開発
- プロジェクト詳細：
  - Next.js(pages router)を利用して SSG / SSR / CSR を使い分けたページを実装
  - タスク管理機能の実装
  - 商談管理機能の実装
  - フルスクラッチでエクセルライクに使用可能なカレンダーを実装
  - 収入管理機能の実装
  - ダッシュボード機能の実装
  - React Query を用いた API 通信の実装
    - 各エンドポイントごとにカスタムフックを実装
  - React Hook Form を用いた複雑なフォーム管理の実装
    - 非制御・制御コンポーネント用のベースとなるラッパーコンポーネントの実装
    - react-select を用いたインクリメンタルサーチ機能の実装
    - debounce 処理を用いたリアルタイム検索機能の改善
    - dnd-kit や react-dnd と合わせてドラッグ＆ドロップ可能な動的なフォームの作成
    - 複雑なビジネスロジックや条件分岐が絡む schema を元にフォームの実装
    - EOF 最適化
  - shadcn / ui + TailwindCSS を用いたデザインシステムの構築とドキュメント整備、ならびに移行
  - Next.js (App Router) × ContentLayer を用いたドキュメント管理
  - Jest + React Testing Library を用いて単体〜結合テストまで幅広く実装
  - Playwright を用いた E2E テストの実装
- その他：
  - フロントエンド基盤の Node.js を v14 → v18 へアップデート
  - 依存ライブラリの脆弱性対応とアップデート
  - ライブラリの継続的アップデートの仕組み化
  - バリデーションライブラリを Yup から Zod へ移行
  - GitHub Actions を用いた自動テストワークフローの作成
  - フロントエンドのビルド時間の短縮
    - Next.js 内部で使用されているコンパイラを Babel から Rust 製の SWC へ移行
  - Plop を用いた雛形コンポーネント作成フローを整備
  - Next.js を v12.3 → v13.5 へ移行
  - Docker 環境を volta, pnpm を用いたローカル環境開発へ移行し、開発生産性を向上
  - ESLint / Prettier にいくつか独自ルールを追加し、フロントエンドの開発基盤を整備
  - テックブログ運営

## 業務外活動

### OSS・個人開発活動

#### 主要リポジトリ

<table>
  <thead>
    <tr>
      <td><b>Projects</b></td>
      <td><b>Lang / FW</b></td>
      <td><b>Stars</b></td>
      <td><b>Forks</b></td>
      <td><b>Issues</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/youliangdao/techfinder"><b>Techfinder</b></a></td>
      <td><img alt="TypeScript" src="https://shields.io/badge/TypeScript-3178C6?logo=TypeScript&logoColor=FFF&style=flat-square" /> <img alt="React" src="https://shields.io/badge/react-black?logo=react&style=for-the-badge" />
      <img alt="Rails" src="https://img.shields.io/badge/-Rails-CC0000.svg?logo=rails&style=flat" />
      </td>
      <td><img alt="Stars" src="https://img.shields.io/github/stars/youliangdao/techfinder?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Forks" src="https://img.shields.io/github/forks/youliangdao/techfinder?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Issues" src="https://img.shields.io/github/issues/youliangdao/techfinder?style=flat-square&labelColor=343b41"/></td>
    </tr>
    <tr>
      <td><a href="https://github.com/youliangdao/self-motivate-image-generator"><b>Seminar Post Generator</b></a></td>
      <td><img alt="TypeScript" src="https://shields.io/badge/TypeScript-3178C6?logo=TypeScript&logoColor=FFF&style=flat-square" /> <img alt="Next.js" src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" /></td>
      <td><img alt="Stars" src="https://img.shields.io/github/stars/youliangdao/self-motivate-image-generator?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Forks" src="https://img.shields.io/github/forks/youliangdao/self-motivate-image-generator?style=flat-square&labelColor=343b41"/></td>
      <td><img alt="Issues" src="https://img.shields.io/github/issues/youliangdao/self-motivate-image-generator?style=flat-square&labelColor=343b41"/></td>
    </tr>
  </tbody>
</table>

#### その他

- [reactjs.org 日本語翻訳プロジェクト](https://github.com/reactjs/ja.react.dev/wiki) の翻訳を一部担当
  - [Pull Request](https://github.com/reactjs/ja.react.dev/pull/571)

### 技術記事投稿

- **Zenn**
  - 現在 13 記事、1,416LIKE
  - https://zenn.dev/youliangdao
- **Qiita**
  - 現在 20 記事、3,193Contributions
  - https://qiita.com/yusuke_blog1026

### 勉強会での登壇

- さくらのマイクロコミュニティ（Web サービス開発者の会）#6
  - [個人開発で挫折する人を救いたい](https://speakerdeck.com/youliangdao/ge-ren-kai-fa-decuo-zhe-sururen-wojiu-itai)
- 所属コミュニティで複数回 LT に登壇
  - [Next.js から見る Web フロントエンドの歴史](https://speakerdeck.com/youliangdao/next-dot-jskarajian-ru-webhurontoendonoli-shi)
  - [SaaS スタートアップで 3 ヶ月間働いて感じた現実（リアル）](https://speakerdeck.com/youliangdao/next-dot-jskarajian-ru-webhurontoendonoli-shi)
  - [Qiita でバズりやすい記事の書き方を伝授する](https://speakerdeck.com/youliangdao/qiitadebazuriyasuiji-shi-noshu-kifang-wochuan-shou-suru)
  - [React って本当に使う意味あるの？〜SPA と React の「キホン」の「キ」](https://speakerdeck.com/youliangdao/react-tuteben-dang-nishi-uyi-wei-aruno-spa-to-react-no-kihon-no-ki)
  - [Puma と Unicorn って結局何なん！？](https://speakerdeck.com/youliangdao/pumatounicorntutejie-ju-he-nan-de06b957-a600-4f57-bdac-df4fdc700479)
  - ["ぼくのかんがえたさいきょうの"勉強法](https://speakerdeck.com/youliangdao/bokufalsekangaetasaikiyoufalse-mian-qiang-fa)
  - [低レイヤへの誘い](https://speakerdeck.com/youliangdao/di-reiyahefalseyou-i)

## 意欲・興味

- 少人数チームで小さく早くリリースし、フィードバックを受けながら改善のサイクルを回していくアジャイルな開発スタイルを好みます
- フロントエンド領域において単なる機能実装だけでなく、全体にレバレッジがかかるであろう部分の設計に興味があります
  - 例えば、テスト戦略の構築や保守性の高いコンポーネントや hooks の設計、CI / CD の最適化など
- フロントエンドだけではなくバックエンド・インフラなどの新しい分野・技術への興味関心が強く、学習しながらアウトプットをすることが得意です
- ドキュメント作成・整備も得意で、ADR やイミュータブルドキュメントモデリングを用いて最小限の運用負荷でドキュメント管理を行えるよう仕組みをつくることも可能です
- 組織文化の形成にも興味関心が強く、勉強会の企画やテックブログの運営などを積極的に行い、開発チームに良い影響を与えていきたいと思っています
- React・Next.js (App Router)・Remix・TypeScript・GraphQL などの技術に興味があります
