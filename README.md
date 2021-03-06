# TiDBデータベース開発規則

目次
---

### [第 1　まえがき](1.まえがき.md)
1. [目的](https://github.com/it2911/tidb_database_develop_manual/blob/main/1.%E3%81%BE%E3%81%88%E3%81%8C%E3%81%8D.md#1-%E7%9B%AE%E7%9A%84)
2. 適用範囲
3. ハイライト
4. 注意事項

### [第2　オブジェクト命名規則](2.%20オブジェクト命名規則.md)
1. 原則
2. データベース命名規則
3. テーブル命名規則
4. フィールド命名規則
5. インデックス命名規則

### [第3　データベースオブジェクト設計](3.データベースオブジェクト設計.md)
1. テーブル設計
2. フィールド設計
3. フィールドデフォルト値
4. インデックス設計
5. 権限設計

### [第4　データモデル設計](4.データモデル設計.md)
1. インテグリティ
2. パフォーマンス
3. スケーラビリティ

### [第5　SQL開発規則](5.SQL開発規則.md)
1. テーブル作成・削除規則
2. select*使用規則
3. 大規模トランザクション処理
4. フィールドでの関数使用規則
5. データ削除規則
6. その他の規則

### [第6　トランザクション制限](6.トランザクション制限.md)
1. 分離レベル
2. SIはファントムリードを解消可能
3. SIはライトスキューを解消不可
4. SAVEPOINTはサポート外
5. 大規模トランザクション制限

### [第7　暗黙の型変換](7.暗黙の型変換.md)
1. インデックス障害
2. 精度低下

### [第8　結果セットの不安定さ](8.セットの不安定さ.md)
1. GROUP BY
2. ORDER BY	
3. GROUP_CONCAT()へのORDER BY不使用による結果セットの不安定さ	

### [第9　インデックス使用上の注意](9.インデックス使用上の注意.md)
1. TiDBのインデックス	
2. 複合インデックス設計	

### [第10　自動インクリメント列使用上の注意](10.自動インクリメント列使用上の注意.md)
1. 原理	
2. ベストプラクティス	
3. 人為的な値割り当ての結果と対応策	

### [第11　TiDBの各種タイムアウト]	(11.TiDBの各種タイムアウト.md)
1. GCタイムアウト
2. トランザクションタイムアウト	
3. SQLタイムアウト	

### [第12　JDBCベストプラクティス](12.JDBCペストプラクティス.md)
1. MySQL Connector/J推奨バージョン	
2. JDBCパラメータ設定	

### [第13　ホットスポットの軽減](13.ホットスポットの軽減.md)
1. ホットスポットへの書き込み	
2. ホットスポットのモニタリングとポジショニング	
3. 書き込みホットスポットの軽減	
4. ホットスポットの読み取り	

### [第14　ページングのベストプラクティス](14.ページングのベストプラクティス.md)
1. ページングクエリ
2. 単一フィールド主キーテーブルのページングバッチ処理	
3. 複合主キーテーブルのページングバッチ処理	

### [第15　固有のシーケンス番号生成方法](15.固有のシーケンス番号生成方法.md)
1. 自動インクリメント列	
2. シーケンス（Sequence）	
3. Snowflake型方法	
4. 数字フィールド設定方法	

### [第16　プロセス規則](16.プロセス規則.md)
