# Tab Dump Privacy Policy / プライバシーポリシー

Effective date / 発効日: September 28, 2026

## English

Tab Dump is a Chrome extension that saves the restorable tabs in the user's current Chrome window so the user can restore them later.

### Data handled

Tab Dump handles the following data only when the user explicitly creates a dump:

- Tab URLs
- Tab titles
- Tab order
- Whether a tab was pinned
- User-entered dump names
- Dump creation timestamps

### How data is used

This data is used only to display saved dumps and reopen their tabs at the user's request.

### Storage and transmission

All data is stored locally on the user's device using `chrome.storage.local`. Tab Dump does not transmit data to the developer or any external server. It does not use analytics, advertising, tracking, remote code, or third-party services.

### Sharing and sale

Tab Dump does not share, sell, or allow human access to user data.

### Retention and deletion

Saved data remains on the user's device until the user deletes an individual dump or uninstalls the extension. Deleting a dump removes that dump from local extension storage. Uninstalling the extension removes its local storage according to Chrome's behavior.

### Permissions

- `tabs`: Used to read the URL, title, order, and pinned state of tabs in the current window; close tabs after a verified save; and reopen saved tabs at the user's request.
- `storage`: Used to store dumps locally in the browser.

Tab Dump does not request host permissions and does not read webpage content.

### Chrome Web Store Limited Use

The use of information received from Chrome APIs adheres to the Chrome Web Store User Data Policy, including the Limited Use requirements.

### Changes

If this policy changes, the updated policy will be published at the same URL with a revised effective date.

### Contact

Questions about this policy may be sent to: **kzmotk+dev@gmail.com**

## 日本語

Tab Dumpは、現在のChromeウィンドウにある復元可能なタブを保存し、あとでユーザーが復元できるようにするChrome拡張です。

### 取り扱うデータ

ユーザーが明示的にDumpを実行した場合に限り、次の情報を取り扱います。

- タブのURL
- タブのタイトル
- タブの順序
- タブのピン留め状態
- ユーザーが入力したDump名
- Dumpの作成日時

### 利用目的

これらのデータは、保存済みDumpの表示と、ユーザー操作によるタブの復元にのみ使用します。

### 保存と送信

すべてのデータは`chrome.storage.local`を使用してユーザーの端末内に保存されます。開発者または外部サーバーへの送信は行いません。アクセス解析、広告、トラッキング、リモートコード、第三者サービスは使用しません。

### 共有と販売

ユーザーデータを第三者と共有または販売せず、人が閲覧できる状態にもなりません。

### 保持と削除

保存データは、ユーザーが個別のDumpを削除するか、拡張機能をアンインストールするまで端末内に保持されます。Dumpを削除するとローカルの拡張機能ストレージから削除されます。拡張機能をアンインストールすると、Chromeの仕様に従ってローカルストレージも削除されます。

### 権限

- `tabs`: 現在のウィンドウにあるタブのURL、タイトル、順序、ピン留め状態の取得、保存検証後のタブ削除、およびユーザー操作によるタブ復元に使用します。
- `storage`: Dumpをブラウザ内へローカル保存するために使用します。

ホスト権限は要求せず、Webページの本文も読み取りません。

### Chrome Web Store Limited Use

Chrome APIから取得した情報の利用は、Limited Use要件を含むChrome Web Store User Data Policyに準拠します。

### 変更

本ポリシーを変更する場合は、発効日を更新したうえで同じURLに掲載します。

### お問い合わせ

本ポリシーに関するお問い合わせ先: **kzmotk+dev@gmail.com**
