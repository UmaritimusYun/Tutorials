学んだ本

- 入門Python3: O'REILLY

メモ

リスト、タプル、辞書、集合違いは何?

リスト

- ミュータブル: 要素の挿入と削除が可能
- 生成方法： [] または list()
- リスト の操作：
  - オフセットによる取り出し：list[0]
  - スライスによるデータ取り出し：list[0:2]
  - 末尾へ要素追加：list.append('add')
  - リストの結合：list1.extend(list2) または list1 += list2
  - 指定したオフセットへの要素追加：list.insert(3, 'add')
  - 指定したオフセットの要素削除：del list[0]
  - 値に基づき要素の削除：list.remove('del')
  - 要素を取り出しつつ削除：list.pop(1) またlist.pop()とすると最後の要素list[-1]が取り出される
  - 要素の値から要素のオフセットを知る：list.index('something')
  - 値の有無を確認：'something' in list  [有 True | 無 False]
  - 値の個数をカウント：list.count('something')
  - 文字列への変換：', '.joint(list) この場合 'add1, add2, add3'
  - 要素の並び替え： 
昇順 list.sort()
降順 list.sort(reverse=Ture)
  - 長さの取得：len(list)
  - 代入
b = a                :aを変更するとbも変わる
    b = a.copy()    :aを書き換えてもbに影響なし

タプル

- イミュータブル: 要素の挿入と削除が不可
- 生成方法： () または tuple(list)



辞書

- リストに似ているがオフセットではなくキーで検索できる
- 生成方法:
dictionary = {"キー":"値"}
dict(list)       : listから辞書を作成

-
