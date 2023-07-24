[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/wXVH1iCY)
# ローカルリポジトリの作成と管理

## 課題（予習を含む）

「コンピュータシミュレーション」について調べ、それぞれの問いに１００字程度で回答しなさい。作業は各自のコンピュータのローカルリポジトリ上の作業用ブランチで行い、GitHub 上でプルリクエストを発行してマージすること。ChatGPT を含め、外部の情報を参照した場合は、参照部分を明記し、参照元を記載すること。

## 記述問題

### コンピュータシミュレーションとは、どのようなものですか。シミュレーションが必要な理由を含めて記述しなさい。

コンピューターシミュレーションとは、コンピューターが色々な出来事を計算し、本物のように再現することです。例としては、天気の予測、自動車の開発などが挙げられます。必要な理由は、実証できない出来事や大規模な出来事を安易に行うためです。


### コンピュータゲームには「シミュレーションゲーム」という分類があります。シミュレーションゲームを一つ取り上げ、「何がシミュレートされているのか」をかんたんにまとめなさい。

Oxygen not includedというゲームがあります。これは、宇宙にコロニーを作るゲームで、街づくりがシミュレーションされています。食糧、空気、資材などを管理し、指揮することでコロニーを作り上げていきます。

### コンピュータシミュレーションのもつ問題点について調べ、記述しなさい。

問題点は、シミュレーションモデルの構築、データの準備、計算時間の短縮化、実現性などが挙げられます。シミュレーションモデルは、数学的な近似によって、限界があり、現実と全く同じように再現できません。

参考文献：
ChatGPT：https://chat.openai.com/c/b450afa4-2c58-4b43-9a81-93cb0e42d905
参照部分「コンピュータシミュレーションは、コンピュータを使って現実世界の事象や現象を仮想的に再現する技術や手法のことを指します。これは、数値計算や数学的なモデルを用いて、物理法則やシステムの振る舞いをコンピュータ上でシミュレートすることにより、現実の実験や観測が難しい場合や高コスト・高リスクな場合に代替手段として利用されます。

気象予測: 大気の流れや温度変化などを数値的にモデル化し、コンピュータ上でシ　　　　ミュレーションを行うことで、未来の気象状況を予測します。

精度の限界：シミュレーションは、モデル化に使用される数学的な近似や仮定によって精度に限界があります。現実の複雑な現象を完全に再現することは難しく、モデルの誤差や不確実性が存在します。
計算時間とリソース：一部のシミュレーションは膨大な計算時間やコンピュータリソースを必要とすることがあります。特に大規模なシステムや長期間にわたるシミュレーションでは、高性能なコンピュータやクラスタリングが必要となります。
モデルの適合性：正確な結果を得るためには、適切なモデル化が必要です。しかし、全ての要因やパラメータを適切にモデル化することは難しい場合があり、不適切なモデル化によって結果が偏る可能性があります。
実験の代替：シミュレーションが実験の代替として利用される場合、シミュレーション結果と実験結果が一致しないケースもあります。実際の現象を考慮しながらシミュレーションを行うことは難しいため、実験とシミュレーションの両方を併用する必要があることもあります。
データの信頼性：シミュレーションには正確な入力データが必要であり、データの信頼性が結果に影響を与えることがあります。データの取得や整理において誤りがある場合、シミュレーションの信頼性が低下する可能性があります。」

https://kotobank.jp/word/%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E3%83%BB%E3%82%B7%E3%83%9F%E3%83%A5%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3-178189
参照部分：「コンピュータを使った計算で現実の世界を模擬すること。」

https://www.google.com/search?q=%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E3%83%BC%E3%82%B7%E3%83%9F%E3%83%A5%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3+%E8%AA%B2%E9%A1%8C&rlz=1C1EQFE_jaJP988JP994&ei=hG-9ZNjzC4fM2roPo6Sf6Ag&ved=0ahUKEwjYxev2uKWAAxUHplYBHSPSB40Q4dUDCA8&uact=5&oq=%E3%82%B3%E3%83%B3%E3%83%94%E3%83%A5%E3%83%BC%E3%82%BF%E3%83%BC%E3%82%B7%E3%83%9F%E3%83%A5%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3+%E8%AA%B2%E9%A1%8C&gs_lp=Egxnd3Mtd2l6LXNlcnAiNOOCs-ODs-ODlOODpeODvOOCv-ODvOOCt-ODn-ODpeODrOODvOOCt-ODp-ODsyDoqrLpoYwyBRAAGKIEMgUQABiiBDIFEAAYogRI8RlQmRhYmRhwA3gBkAEAmAFsoAFsqgEDMC4xuAEDyAEA-AEBwgIKEAAYRxjWBBiwA-IDBBgAIEGIBgGQBgo&sclient=gws-wiz-serp
参照部分：
「コンピュータでのシミュレーションの技術的な課題には, シミュレーションモデルの構築と検証の容易化, シミュレー ションの実行用入力データの準備の容易化及びシミュレーシ ョンの実行に要する計算時間の短縮がある。」

