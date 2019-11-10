バイトニックソートを実装した。
今の所動かせるのはベンチマークのみ
```bash
# テスト
cargo test

# ベンチマーク
# <bits> 何ビットのデータをソートするか。(26 ~ 28が手軽に終わる範囲)
cargo run --release --example benchmarks -- <bits>
```
