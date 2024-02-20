---
title: "UTokyo Accountのパスワード有効期限の修正について"
toc: false
---

<div style="text-align: right;">2023年12月6日</div>

いつも本学の情報システムの運営にご協力いただきありがとうございます．

このたび，一部の方のUTokyo Accountについて，システムの不備により，**パスワードの有効期限に設定の誤りがある**ことが判明しました．本日，設定を修正する作業を行いましたので，お知らせいたします．該当する方には，具体的な修正内容（修正前後の有効期限）をメールでご連絡していますので，**修正後の有効期限までに，[UTokyo Account利用者メニュー](https://utacm.adm.u-tokyo.ac.jp/webmtn/LoginServlet)からUTokyo Accountのパスワードを変更していただく**ようお願いいたします．なお，パスワード変更の際に多要素認証が有効化済みであれば，変更後のパスワードは有効期限が無期限となります．

ご迷惑をおかけし，申し訳ありません．

本件についてご不明な点がある場合は，[サポート窓口](/support/)へお問い合わせください．その際は，「UTokyo Accountのパスワード有効期限の修正について」に関する件である旨をお知らせください．

## 問題の経緯

2023年3月9日に，UTokyo Accountのパスワードに関する取り扱いの変更を行いました．変更前のパスワード有効期間は一律で365日（1年）間でしたが，変更後は，多要素認証を有効化している場合は無期限，多要素認証を有効化していない場合は397日（1年+1ヶ月）間となっています．また，パスワードに求められる最小の文字数の基準が8文字から12文字に変わりました．

この取り扱い変更後，2023年4月21日までの間，多要素認証を有効化する操作を行うとパスワード有効期限が無期限となる挙動となっておりました．しかし，取り扱い変更前に設定したパスワードについては，新しい文字数の基準を満たしていない可能性があるため，このように無期限となる挙動は誤りでした．

当該の挙動自体については既に修正しておりますが，誤って設定された有効期限はそのままとなっていたため，今回有効期限を修正することとしたものです．

なお，パスワードはシステム内で暗号化（ハッシュ化）されて保存されており，管理者にも元のパスワードは分からないようになっているため，実際のパスワードの文字数にかかわらず，挙動に不備のあった期間に操作を行ったすべての方を対象としております．

修正後の有効期限は，直近のパスワード変更日が 2023-01-06 （本日の334日前）以前の方は本日から31日後である 2024-01-06 と，それ以外の方はパスワード変更日から365日後となっています．