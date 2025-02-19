# sample-github-actions
Github Actions を動かすだけのサンプル

## mainブランチにマージされている

- on push: 動く
- on workflow_dispatch: 動く

## mainブランチにマージされていない（ブランチにあるだけ）

- on push: 動く（ブランチを指定する必要あり）
- on workflow_dispatch: 動かない（Github Actionsの画面に出てこない）

## その他注意事項

`.github/workflows/`直下にワークフローファイルを置かないと認識されない。

※サブディレクトリに配置しても認識されない
