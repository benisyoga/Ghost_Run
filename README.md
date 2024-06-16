# Ghost_Run

プロジェクトファイルはGoogleDriveから  
リンク：https://drive.google.com/drive/folders/1YpGV111FEzwQ2OErsY5tfHQ6_fG84YRZ?usp=sharing

使用ゲームエディタ：Unity  
使用言語：#c  
開発体制：個人開発  
開発期間：２週間  

Gitから実行ファイルをダウンロードした場合はMy project_Dataのzipファイルを解凍してください。  

操作方法：  
・タイトル画面、リザルト画面、ポーズメニュ  
上下キー...選択しているボタン・スライダーを切り替える  
左右キー...スライダーを操作  
エンターキー...ボタンを決定  

・ゲーム画面  
ＡＤキー/左右キー...左右移動  
Ｗキー/上キー...上昇  
Ⅴキー...透明化  
Ｐキー...ポーズ画面  

ルール：  
・時間経過でスコアが少しずつ増える  
・お菓子を取るとスコアが大幅に増える  
・棘や鉄球などのトラップに当たるとライフが１減る  
・ライフが０になったらゲームオーバー  
・ゲージを消費することで上昇/透明化することができる  
・ゲージが無くなると完全に回復しきるまで上昇/透明化できなくなる  
・透明化中はトラップに当たらないが、お菓子を取ることもできない  

開発目的：  
3Dゲームの作り方を学ぶため。コリジョンを用いた当たり判定の扱い方に慣れるため  

こだわったところ：  
・通常の3Dランゲームに「オバケらしさ」のアクションである浮遊と透明化を加えてアレンジしたところ  
・コルーチンを使用して演出や地形の自動生成のスクリプトを簡略化したところ  
・描写するオブジェクトの数を制限して負荷を減らすために、地形を生成しすぎないようした  
・同様の理由で通り過ぎた地形は削除するようにした  
・オプション画面を実装し、音量をユーザーが自由に調整できるようにした  
・シーンの切り替えやスコアの管理など、「I_am_not_robot」と共通している部分もより管理をしやすいようにスクリプトを改善した  
