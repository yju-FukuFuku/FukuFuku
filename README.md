# [FukuFuku]()

<div align="center" style="display:flex;">
    <img src="logo.png" width="100" alt="logo"/>
</div>

# 目次

[1. チームメンバー](#チームメンバー)

[2. プロジェクト紹介](#プロジェクト紹介)

[3. 技術スタック](#技術スタック)

[4. アーキテクチャ](#アーキテクチャ)

[5. ERD](#ERD)

[6. API設計](#API設計)

[7. リポジトリ](#リポジトリ)

[8. コアー機能](#コアー機能)

# チームメンバー

|[カン・ジュウォン](https://github.com/Z00One)|[キム·ギュミン](https://github.com/kyumin1227)|[パク・ジョンミン](https://github.com/dorimu0)|[ソク・ジンソク](https://github.com/Lainari)|
| :-: | :-: | :-: | :-: |
|<img src="https://avatars.githubusercontent.com/u/102473964?v=4" width=400px alt="ジュウォン"/>|<img src="https://avatars.githubusercontent.com/u/68456336?v=4" width=400px alt="ギュミン"/>|<img src="https://avatars.githubusercontent.com/u/121004915?v=4" width=400px alt="ジョンミン"/>|<img src="https://avatars.githubusercontent.com/u/108247620?v=4" width=400px alt="ジンソク"/>|
|Backend|Frontend|Frontend|Frontend
<br>

# プロジェクト紹介
FukuFukuは永進専門大学日本IT科の学生たちが現地学期制での経験を共有したり、グルメを推薦するプラットフォームです。 <br>
FukuFukuはFukuoka(福岡)のFuku(福)にちなんで作った名前で、福岡に現地学期制に行く学生たちがお互いに掲示文を残してお互いの経験を共有することができます。 <br>
掲示文を作成して自分の経験を共有したり、グルメ店を推薦することができ、いいねとコメント機能を通じてお互いに疎通したり、気に入った文章が好きです リストに保存することもできます。<br>
<br>

# 技術スタック
### フロントエンド
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

### バックエンド
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)

### コラボレーションツール
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Gather](https://img.shields.io/badge/gather-%23007ACC.svg?style=for-the-badge&logo=ros&logoColor=white)

### 配布
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)<br>
<br>

# アーキテクチャ
![FukuFuku_architecture](https://github.com/yju-FukuFuku/FukuFuku/assets/102473964/342d367c-0933-4eb5-9aef-909260c8abe2)
<br>

# ERD
![ERD](https://github.com/yju-FukuFuku/FukuFuku/assets/102473964/cdb5e54a-e65d-4de3-8698-55d0ecad3684)
<br>

# API設計
こちらの[Notion](https://rhinestone-tarragon-315.notion.site/cc21cc2dbaa148ca806adc547dae3f89?v=3b325685b7f94afdb7f1ed09765e3abf)のページをご参照ください。<br>
<br>

# リポジトリ
- [フロントエンド](https://github.com/yju-FukuFuku/FukuFuku_Frontend-repo)
- [バックエンド](https://github.com/yju-FukuFuku/FukuFuku_Backend-repo)
<br>

# コアー機能
### 投稿CRUD
  - 投稿の作成時に画像をアップロードするとストレージに保存され、画像をアップロードしないと基本画像が適用されます。
  - 投稿の画像を修正すると、既存の画像はストレージから削除されます。
  - 投稿を削除すると、その投稿の画像はストレージから削除されます。
### 管理者機能
  - 不適切なコメントの場合は削除ができます。
  - 不適切な投稿を削除、修正することができます。

|投稿作成|
| :-: |
|![게시글 생성](https://github.com/yju-FukuFuku/FukuFuku/assets/102473964/bdff1a96-b2b2-4dea-b290-5ae743123083)|

|投稿修正|
| :-: |
|![게시글 수정](https://github.com/yju-FukuFuku/FukuFuku/assets/102473964/c49a32b6-75b5-4115-8c24-6c1304ba096e)|

|投稿削除|
| :-: |
|![게시글 삭제](https://github.com/yju-FukuFuku/FukuFuku/assets/102473964/a668df4c-5dec-4f70-a47f-a12c07cd8120)|

|管理者機能|
| :-: |
|![관리자 권한](https://github.com/yju-FukuFuku/FukuFuku/assets/102473964/a7b309c6-9f3c-4be4-9e6a-d85413ed5973)|
