# BUNNY GARDEN 2 - フリーカメラ＆チェキ拡張MOD

BUNNY GARDEN 2 のフリーカメラを改善し、チェキ撮影を快適にするMODセットです。

## MOD一覧

### BG_FreeCamera

- **Shift＝UIモード**: Shiftキーを押している間、カメラ位置を固定したままカーソルが解放され、ゲーム内のボタン操作が可能。チェキ撮影中の衣装変更やポーズ変更などに便利
- **F11＝GUI非表示**: すべてのUIを非表示にしてクリーンなスクリーンショットが撮れます

### BG_ChekiTimeStop
チェキ撮影中（PHOTOGRAPHING状態）の制限時間を自動的に凍結します。時間を気にせず自由にカメラアングルを調整できます。

## 必要環境

- BUNNY GARDEN 2（Steam版）
- BepInEx 6 Bleeding Edge（Unity.Mono, x64）
- [BunnyGarden2FixMod](https://github.com/noeleve/BunnyGarden2FixMod)（BG_FreeCameraの前提MOD）

## インストール

1. BepInEx 6 BE（Unity.Mono, win-x64）をゲームフォルダに導入
2. BunnyGarden2FixMod を導入
3. 一度ゲームを起動して閉じる（`BepInEx/plugins` フォルダが生成されます）
4. 使いたいMODの `.dll` ファイルを `BepInEx/plugins/` にコピー
5. ゲームを起動

## 操作方法

| キー | 機能 |
|------|------|
| F5 | フリーカメラ ON/OFF（FixMod機能） |
| F6 | カメラ位置固定モード ON/OFF（FixMod機能） |
| WASD / 矢印キー | カメラ移動 |
| Q / E | カメラ上昇 / 下降 |
| Ctrl | 低速移動 |
| マウス左/右クリック | マウスビュー切替 |
| Shift（押し中） | UIモード（カーソル解放＋ゲーム操作可能） |
| F11 | 全UI非表示/表示 |

## 注意事項

- BG_FreeCamera は BunnyGarden2FixMod が必須です（単体では動作しません）
- BG_ChekiTimeStop は単体で動作します
- セーブデータには影響しません
- UI非表示中もF11で復帰できます
