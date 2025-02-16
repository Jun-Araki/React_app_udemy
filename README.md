# 開発したアプリ
![Screen Recording 2025-01-30 at 9](https://github.com/user-attachments/assets/8e299a99-7044-4a17-9ef1-0a295c9f357d)

# 解説記事
https://qiita.com/TS1engineer/items/f25bd03688033aa0e69b

# 初めに
Reactは案件で軽く触れた程度ですが、Reactのプロジェクトに入りたいと思い、再度学習を行いました。
その中で、じゃけさんのUdemy講座がわかりやすいと評判だったので、早速購入しました。
その内容をまとめていきます！

# 0. 教材
じゃけさんが作成されたReact v18対応のUdemy教材。
初心者がReactを学習する想定で解説されているので、非常にわかりやすかった！

![image.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2674841/76c82656-fee5-0e8e-1962-a471c04d71fa.png)


https://www.udemy.com/course/modern_javascipt_react_beginner/?couponCode=KEEPLEARNING

# 1. JavaScriptの基礎を理解する
いきなりReactを学ぶのではなく、JavaScriptの基礎を理解する。React開発でもJavaScriptの知識が必要になるので、理解することが目的。
理解した内容は以下。
- JavaScriptとは
- DOMと仮想DOMの違い
- npm, yarnのパッケージマネージャー
- ECMAScriptとは
- モジュールハンドラーとトランスパイラ
- SPAとは
- const, letの変数宣言
- テンプレート文字列
- アロー関数
- 分割代入
- デフォルト値
- オボジェクトの省略記法
- スプレッド構文
- map, filter
- 三項演算子
- 論理演算子

Githubは以下
https://github.com/Jun-Araki/JS_udemy/blob/main/src/index.js

# 2. JavaScriptでTodoアプリを作る
理解した基礎知識をもとに、実際にJavaScriptでTodoアプリを作る。

作成したアプリは以下
![Screen Recording 2025-01-30 at 9.gif](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2674841/d5c770b6-d29f-7c61-4930-e5ae4c315298.gif)

Githubは以下
https://github.com/Jun-Araki/JS_todo_app_udemy/

【機能】
- タスク追加機能
- タスク削除機能
- タスク完了機能
- タスク戻す機能

# 3. Reactの基礎を理解する
ここからReactの基礎機能を理解していく。
- JSX記法のルール
- コンポーネント
- Props
- State
- 再レンダリング useEffect
- defalut export, named export

Githubは以下
https://github.com/Jun-Araki/React_Udemy/tree/main/src

# 4. Reactで同じTodoアプリを作る
2.で作ったアプリをReactで作ることで、Reactになるとどのように変わるのかを体感する。
JavaScriptは手続型、Reactは宣言型の通り、非常に短いコードで書くことができて感動した！

作成したアプリは以下
![Screen Recording 2025-01-30 at 9.gif](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/2674841/d5c770b6-d29f-7c61-4930-e5ae4c315298.gif)

Githubは以下
https://github.com/Jun-Araki/React_app_udemy

# 5.学習を終えて
JavaScriptの基礎学習からTodoアプリを作り、同じことをReactで実装することで、Reactの良さ確認することができた。記述量が大幅に減って、コンポーネント化されたことで、コードが体系化されて、非常に可読性が高い言語であることを理解できた！引き続き、Reactで別のアプリを作っていきたい。
