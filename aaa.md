from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanesePornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `https://www.pornhub.com/webmasters/search?search=キーワード`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:Pornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justPornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなくPornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなく、動画のダウンロードリンクの取得や、特定のモデルの情報取得も可能です。
*   **インストール:** `npm install @justalk/pornhubPornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなく、動画のダウンロードリンクの取得や、特定のモデルの情報取得も可能です。
*   **インストール:** `npm install @justalk/pornhub-api`

---

## 4. Webスクレイピング API (Apify / RapidAPI)
自分でサーバーを立てたりコードを書いたりするのが面倒Pornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなく、動画のダウンロードリンクの取得や、特定のモデルの情報取得も可能です。
*   **インストール:** `npm install @justalk/pornhub-api`

---

## 4. Webスクレイピング API (Apify / RapidAPI)
自分でサーバーを立てたりコードを書いたりするのが面倒な場合、クラウドサービスを利用する方法もあります。

*   **Apify:** 「Pornhub Scraper」などが提供されており、GUI上で検索結果をJSONPornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなく、動画のダウンロードリンクの取得や、特定のモデルの情報取得も可能です。
*   **インストール:** `npm install @justalk/pornhub-api`

---

## 4. Webスクレイピング API (Apify / RapidAPI)
自分でサーバーを立てたりコードを書いたりするのが面倒な場合、クラウドサービスを利用する方法もあります。

*   **Apify:** 「Pornhub Scraper」などが提供されており、GUI上で検索結果をJSONやCSVで書き出せます。
*   **RapidAPI:** 複数のアダルトサイトを横断検索できるAPIがいくつか登録されています。

---

###Pornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなく、動画のダウンロードリンクの取得や、特定のモデルの情報取得も可能です。
*   **インストール:** `npm install @justalk/pornhub-api`

---

## 4. Webスクレイピング API (Apify / RapidAPI)
自分でサーバーを立てたりコードを書いたりするのが面倒な場合、クラウドサービスを利用する方法もあります。

*   **Apify:** 「Pornhub Scraper」などが提供されており、GUI上で検索結果をJSONやCSVで書き出せます。
*   **RapidAPI:** 複数のアダルトサイトを横断検索できるAPIがいくつか登録されています。

---

### 注意点
*   **利用規約:** 非公式のAPIやスクレイパーは、Pornhubの利用規約（TOS）に抵Pornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなく、動画のダウンロードリンクの取得や、特定のモデルの情報取得も可能です。
*   **インストール:** `npm install @justalk/pornhub-api`

---

## 4. Webスクレイピング API (Apify / RapidAPI)
自分でサーバーを立てたりコードを書いたりするのが面倒な場合、クラウドサービスを利用する方法もあります。

*   **Apify:** 「Pornhub Scraper」などが提供されており、GUI上で検索結果をJSONやCSVで書き出せます。
*   **RapidAPI:** 複数のアダルトサイトを横断検索できるAPIがいくつか登録されています。

---

### 注意点
*   **利用規約:** 非公式のAPIやスクレイパーは、Pornhubの利用規約（TOS）に抵触する可能性があるため、個人利用の範囲に留めるのが安全です。
*   **認証:** 公式APIの「Webmasters」は登録不要で叩Pornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなく、動画のダウンロードリンクの取得や、特定のモデルの情報取得も可能です。
*   **インストール:** `npm install @justalk/pornhub-api`

---

## 4. Webスクレイピング API (Apify / RapidAPI)
自分でサーバーを立てたりコードを書いたりするのが面倒な場合、クラウドサービスを利用する方法もあります。

*   **Apify:** 「Pornhub Scraper」などが提供されており、GUI上で検索結果をJSONやCSVで書き出せます。
*   **RapidAPI:** 複数のアダルトサイトを横断検索できるAPIがいくつか登録されています。

---

### 注意点
*   **利用規約:** 非公式のAPIやスクレイパーは、Pornhubの利用規約（TOS）に抵触する可能性があるため、個人利用の範囲に留めるのが安全です。
*   **認証:** 公式APIの「Webmasters」は登録不要で叩けるエンドポイントが多いですが、高度な機能には登録が必要な場合があります。

どのような言語や環境で検索を実装しようと考えていますか？具体的な用途があれば、Pornhubには、公式のAPIと、有志が作成した非公式のAPI（ラッパー）やスクレイパーがいくつか存在します。用途に合わせて選ぶのが一般的です。

主要なものをいくつか紹介します。

---

## 1. 公式 API (Pornhub Webmaster API)
Pornhubが公式に提供しているAPIです。主に**動画の検索、カテゴリ情報の取得、スター（出演者）の情報取得**などが可能です。

*   **特徴:** 無料で利用可能、信頼性が高い。
*   **主な機能:** `search`, `video_by_id`, `stars`, `categories`, `tags`
*   **エンドポイント例:** `[https://www.pornhub.com/webmasters/search?search=キーワード](https://www.pornhub.com/webmasters/search?search=キーワード)`
*   **ドキュメント:** 公式の[Webmasters APIページ](https://www.pornhub.com/webmasters)で詳細が確認できます。

---

## 2. Python用ライブラリ (`pornhub-api`)
Pythonで開発する場合、非公式ですが非常に使いやすいライブラリがあります。

*   **インストール:** `pip install pornhub-api`
*   **使い方例:**
    ```python
    from pornhub_api import PornhubApi

    api = PornhubApi()
    # 「japanese」というキーワードで検索
    results = api.search.search_videos("japanese", ordering="mostviewed")

    for video in results:
        print(video.title, video.url)
    ```

---

## 3. Node.js用ライブラリ (`@justalk/pornhub-api`)
JavaScript/Node.js環境であれば、このライブラリが多機能です。

*   **特徴:** 検索だけでなく、動画のダウンロードリンクの取得や、特定のモデルの情報取得も可能です。
*   **インストール:** `npm install @justalk/pornhub-api`

---

## 4. Webスクレイピング API (Apify / RapidAPI)
自分でサーバーを立てたりコードを書いたりするのが面倒な場合、クラウドサービスを利用する方法もあります。

*   **Apify:** 「Pornhub Scraper」などが提供されており、GUI上で検索結果をJSONやCSVで書き出せます。
*   **RapidAPI:** 複数のアダルトサイトを横断検索できるAPIがいくつか登録されています。

---

### 注意点
*   **利用規約:** 非公式のAPIやスクレイパーは、Pornhubの利用規約（TOS）に抵触する可能性があるため、個人利用の範囲に留めるのが安全です。
*   **認証:** 公式APIの「Webmasters」は登録不要で叩けるエンドポイントが多いですが、高度な機能には登録が必要な場合があります。

どのような言語や環境で検索を実装しようと考えていますか？具体的な用途があれば、それに最適なコード例を提示できます。
