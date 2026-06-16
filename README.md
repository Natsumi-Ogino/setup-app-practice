# setup-app-practice

## 概要

COACH TECH 教材 Tutorial 9-1「環境構築ハンズオン」で作成した成果物です。
Laravel Sail と Docker を使って、Tutorial 9〜10 のハンズオンで使う開発環境を構築しました。

## 使用技術

- PHP 8.x
- Laravel 10.x
- Laravel Sail（Docker Compose）
- MySQL
- phpMyAdmin

## 学んだこと

- sail up -d のコマンド一つで、PHP・MySQL・phpMyAdmin がまとめて起動できて便利だと感じた
- compose.yaml に設定を追加することで、phpMyAdmin が使えるようになることを知った

## 動作確認

- ブラウザで http://localhost にアクセスし、Laravel のウェルカムページが表示されることを確認した
- ブラウザで http://localhost:8080 にアクセスし、phpMyAdmin の画面が表示されることを確認した
