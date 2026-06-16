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
- Laravel Sail を使って、Docker ベースの開発環境を構築する方法
- compose.yaml に phpMyAdmin を追加して、ブラウザからデータベースを管理できるようにする方法
- sail artisan key:generate でアプリケーションキーを生成する役割

## 動作確認
- ブラウザで http://localhost にアクセスし、Laravel のウェルカムページが表示されることを確認した
- ブラウザで http://localhost:8080 にアクセスし、phpMyAdmin の画面が表示されることを確認した