# 慶應義塾大学SF研究会

> [!TIP]
> こちらはOrganization 未参加に向けた表示です。organizationへの参加が完了した方は、枠外右、もしくは下にあるトグルをPublic からMembersに変更し、メンバー向けのOverviewを、参照してください。

githubアカウントを登録して、当organizationに招待されることで、会誌の編集フォルダ、会計情報を集めたフォルダ、等々当会の全ての情報にアクセスできます。

アクセス権の欲しいSF会員はアカウント登録後に、役員（現在はおくの）に登録したメールアドレスを送ってください。  
招待メールを送るので、承認してください。

GitHub の仕様上、招待を承諾するまでは正式なメンバーとしてカウントされず、リポジトリへのアクセスも制限されます。

- [慶應義塾大学SF研究会](#慶應義塾大学sf研究会)
	- [Organization への参加手順](#organization-への参加手順)
		- [1. アカウント作成・二段階認証の設定](#1-アカウント作成二段階認証の設定)
		- [2. 招待メールの受取・承認](#2-招待メールの受取承認)
			- [方法1](#方法1)
			- [2. GitHub ウェブサイト上で直接承諾する手順](#2-github-ウェブサイト上で直接承諾する手順)
	- [パブリック向けとメンバー向けの表示切り替えの方法](#パブリック向けとメンバー向けの表示切り替えの方法)
	- [1. 表示モードの切り替え方法（確認手順）](#1-表示モードの切り替え方法確認手順)
	- [2. パブリック向けプロフィールの編集方法](#2-パブリック向けプロフィールの編集方法)
	- [3. メンバー向け表示（ダッシュボード）のカスタマイズ](#3-メンバー向け表示ダッシュボードのカスタマイズ)
	- [4. 注意点](#4-注意点)　　

登録後にすること


## Organization への参加手順

### 1. アカウント作成・二段階認証の設定

一般的なwebサービスと同様の手順。[サイト](https://github.com/)にアクセスし、サインアップからメールアドレスとパスワードを登録する。メールアドレスは自分が一番よく使うものがよい。

登録後は二段階認証も設定しよう。（強く推奨しますが、任意とします。）  
二段階認証設定時には、スマホなどの紛失に備えてリカバリーコードをダウンロードしておく。

- [アカウントの作成方法](https://docs.github.com/ja/get-started/start-your-journey/creating-an-account-on-github)
- [二段階認証の設定方法](https://qiita.com/kanamekun/items/c307c942508e9d64c35b)

### 2. 招待メールの受取・承認

二つの方法があります。

#### 方法1

招待メールから承諾する手順

最も一般的な方法です。GitHub アカウントに登録しているメールアドレス宛に通知が届きます。

- **メールを確認する**
    件名が `[GitHub] @(ユーザー名) has invited you to join the @(組織名) organization` というメールを探します。
- **ボタンをクリックする**
    本文内にある **[Join @(組織名)]** という緑色のボタンをクリックします。
- **ブラウザで承認する**
    GitHub のサイトにリダイレクトされます。画面上の **[Join (組織名)]** ボタンをクリックすれば完了です。
      * ※もし 2 要素認証（2FA）を有効にしていない組織の場合、設定を求められることがあります。

#### 2. GitHub ウェブサイト上で直接承諾する手順

メールが見つからない、またはメールを開きたくない場合は、GitHub にログインした状態で直接操作が可能です。

1.  **招待用ページへアクセスする**
    ブラウザで以下の URL に直接アクセスします（`(組織名)` は招待元の名前に置き換えてください）。
    `https://github.com/orgs/(組織名)/invitation`
2.  **選択肢を選ぶ**
    画面に招待の詳細が表示されます。
      * **Join (組織名)**：参加を承諾します。
      * **Decline**：招待を辞退します。

> [!NOTE]
> * **有効期限：** 招待メールの有効期限は **7 日間** です。期限が切れた場合は、管理者に再送を依頼する必要があります。
<!-- > * **アカウントの確認：** 招待メールを受け取ったメールアドレスと、現在ログインしている GitHub アカウントが一致しているか確認してください。
> * **2 要素認証（2FA）：** 組織のポリシーで 2FA が必須となっている場合、2FA を設定するまで参加を完了できないことがあります。 -->

## パブリック向けとメンバー向けの表示切り替えの方法

GitHub の Organization の Overview（概要）ページには、**「パブリック（一般公開）用」**と**「メンバー用」**の 2 種類の表示を切り替えて編集・確認する機能があります。

オーガナイゼーションへの登録が未完了の場合、パブリックしか見れない。オーガナイゼーションへの参加が完了すると、メンバーの方も見れるようになる。

## 1. 表示モードの切り替え方法（確認手順）

Organization のメインページ（Overview）にアクセスすると、画面右上に表示を切り替えるタブまたはドロップダウンが表示されます。

1.  **GitHub で Organization のトップページを開く**
    `https://github.com/（組織名）` にアクセスします。
2.  **表示を切り替える**
    ヘッダー部分（通常はリポジトリ一覧などの上部）にある **[View as]** というボタンをクリックします。
    * **Public:** ログインしていないユーザーや、組織外のユーザーに見える状態を確認できます。
    * **Member:** 組織に所属しているメンバーにだけ見える、内部リポジトリやアクティビティを含んだ状態を確認できます。

## 2. パブリック向けプロフィールの編集方法

外部（非メンバー）に対して、組織の紹介文や README を表示させる設定です。

1.  **README プロフィールの作成**
    組織内に `.github` という名前のパブリックリポジトリを作成し、その中に `profile/README.md` を作成します。
    * このファイルに記述した内容が、**Public** モードの Overview ページ上部に表示されます。
2.  **基本情報の変更**
    [Settings] > [General]（または [Organization profile]）から、組織名、ロゴ、説明文、URL、メールアドレスなどを編集できます。これらは Public/Member 両方に反映されます。

---

## 3. メンバー向け表示（ダッシュボード）のカスタマイズ

メンバーがログインした際に表示される内容は、主に GitHub 側で自動生成されますが、管理者は以下の調整が可能です。

* **リポジトリのピン留め (Pinned repositories):**
    Overview ページで [Customize pins] をクリックし、最大 6 つのリポジトリを固定できます。これは Public モードで表示するものと、Member モードで表示するものを共通または個別に設定できます。
* **プライベートリポジトリの可視性:**
    Member モードでは、メンバーがアクセス権を持つプライベートリポジトリが自動的に一覧に表示されます。これは Public モードでは一切表示されません。

## 4. 注意点

* **権限:** 表示の切り替え（View as）自体は誰でも可能ですが、README の編集や設定の変更には **Owner（オーナー）** または **Admin（管理者）** 権限が必要です。
* **キャッシュ:** README を更新してもすぐに反映されない場合は、ブラウザをリロードするか数分待ってから再度確認してください。

---

**情報源:** [GitHub Docs - 組織のプロフィールについて](https://docs.github.com/ja/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

