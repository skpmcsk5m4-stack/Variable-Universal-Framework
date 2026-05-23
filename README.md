# Variable-Universal-Framework

**「統一ではなく、調律へ」**  
AIを「使う」ことから「統治する」へ。軽量でモデル非依存なAIガバナンスフレームワーク。

## コンセプト

VUFは、AIに対して**ユーザー主権**を確立するための軽量フレームワークです。

- **Fact Anchor**（事実の絶対固定）を不変の大地とし
- **守破離プロセス**で推論を段階的に管理
- **Romance Containment**で創造性と妄想を適切に制御

一つの正解を押しつける「統一」ではなく、各ユーザー・各AIの個性を活かした**調律**を目指します。

## コア構成

- **F.A.L. v2.0** - Fact Anchor Logic（事実の絶対固定）
- **守破離プロセス** - Shu（精密） / Ha（創造） / Ri（超越）
- **SAM_Light v1.1** - 最小限の自己監視機構
- **Tag_Based Romance Containment** - ロマン・仮説の可視化と管理

## 特徴

- モデル非依存（Grok, Claude, Gemini, GPTなど全て対応）
- 極めて軽量（JSONベースで簡単に運用可能）
- ユーザー主権を最優先
- 「これ以上は足さない。これ以下にも落とさない。」というミニマリズム

## 関連資料

- [VUF v2.1 適応レポート「統一ではなく、調律へ」](https://note.com/cool_sloth3599/n/n5884ade4a5f5) 
  （六AI比較・実運用検証を含む詳細レポート）
- [VUFの比喩的表現による解説　アメリカンマッチョイズム編(偏見)](https://note.com/cool_sloth3599/n/n5d15a74e4dce)
- [VUF適応Geminiに直撃インタビュー](https://note.com/cool_sloth3599/n/na0140bad220f)

## 使い方

1. `framework.json` を読み込む
2. 自分の `User_Core_Thinking` を定義
3. 必要に応じて守破離を切り替える

```json
{
  "vuf_version": "v2.1_CORE",
  "status": "STABLE_MINIMAL",
  "philosophy": "事実を大地に、個性を調律し、人間が主導権を握る"
}
```

## ライセンス

MIT License（自由に fork・改変・商用利用可能です）

---
