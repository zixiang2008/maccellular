# maccellular · Multilingual Project Guide

<p align="center">
  <a href="#简体中文">中文</a> ·
  <a href="#english">English</a> ·
  <a href="#日本語">日本語</a> ·
  <a href="#ภาษาไทย">ไทย</a>
</p>

> Self-hosted phone and SMS for a physical SIM connected to a home Mac.

---

## 简体中文

### 项目概览

- 类型：原创仓库
- 可见性：public
- 主要技术：Go
- 默认分支：`main`

本仓库源自 [上游项目](https://github.com/yuexiazhuojiu-byte/MacCellular)，上游文档与许可证条款仍是最终依据。

### 架构与设计原则

项目以 Go 为主要技术载体。代码、配置、静态资源与文档按仓库原有结构组织。维护时应保持最小改动、兼容原有入口，并在合并前运行项目现有的构建与测试。

### 使用方法

1. 克隆仓库：`git clone https://github.com/zixiang2008/maccellular.git`
2. 阅读原 README 及依赖清单，确认当前分支需求。
3. 安装依赖：`go mod download`
4. 启动或构建：`go run .`
5. 验证变更：`go test ./...`

命令为通用入口；若与原 README 不同，以原项目文档和仓库脚本为准。请勿将密码、API 密钥、私钥或生产环境配置提交到 Git。

---

## English

### Project overview

- Type: Original repository
- Visibility: public
- Primary stack: Go
- Default branch: `main`

This repository is derived from [the upstream project](https://github.com/yuexiazhuojiu-byte/MacCellular). Upstream documentation and licensing remain authoritative.

### Architecture and design principles

The project uses Go as its primary technical foundation. Source code, configuration, static assets, and documentation follow the repository's existing structure. Maintenance should favor small compatible changes and run the existing build and test checks before merge.

### Usage

1. Clone: `git clone https://github.com/zixiang2008/maccellular.git`
2. Read the original README and dependency manifest for branch-specific requirements.
3. Install: `go mod download`
4. Run or build: `go run .`
5. Verify: `go test ./...`

These are safe general entrypoints. If they differ from the original README, follow the repository's own scripts and upstream documentation. Never commit passwords, API tokens, private keys, or production configuration.

---

## 日本語

### プロジェクト概要

- 種別: オリジナルリポジトリ
- 公開範囲: public
- 主な技術: Go
- デフォルトブランチ: `main`

このリポジトリは [アップストリーム](https://github.com/yuexiazhuojiu-byte/MacCellular) から派生しています。上流のドキュメントとライセンスが優先されます。

### アーキテクチャと設計原則

Go を主要な技術基盤とし、ソース、設定、静的アセット、文書は既存のリポジトリ構成に従います。保守では小さく互換性のある変更を優先し、マージ前に既存のビルドとテストを実行します。

### 使い方

1. クローン: `git clone https://github.com/zixiang2008/maccellular.git`
2. 元の README と依存関係を確認します。
3. インストール: `go mod download`
4. 実行またはビルド: `go run .`
5. 検証: `go test ./...`

コマンドが元の README と異なる場合は、リポジトリ固有のスクリプトと上流文書を優先してください。パスワード、API トークン、秘密鍵、本番設定を Git にコミットしないでください。

---

## ภาษาไทย

### ภาพรวมโครงการ

- ประเภท: รีพอสิทอรีต้นฉบับ
- การมองเห็น: public
- เทคโนโลยีหลัก: Go
- บรานช์เริ่มต้น: `main`

รีพอสิทอรีนี้ต่อยอดจาก [โครงการต้นทาง](https://github.com/yuexiazhuojiu-byte/MacCellular) โดยให้ถือเอกสารและสัญญาอนุญาตของต้นทางเป็นหลัก

### สถาปัตยกรรมและหลักการออกแบบ

โครงการใช้ Go เป็นพื้นฐานหลัก โดยจัดซอร์สโค้ด การตั้งค่า ไฟล์สถิต และเอกสารตามโครงสร้างเดิม ควรแก้ไขทีละน้อยโดยรักษาความเข้ากันได้ และรันการสร้างและทดสอบเดิมก่อนรวมโค้ด

### วิธีใช้

1. โคลน: `git clone https://github.com/zixiang2008/maccellular.git`
2. อ่าน README เดิมและไฟล์รายการ dependency
3. ติดตั้ง: `go mod download`
4. รันหรือสร้าง: `go run .`
5. ตรวจสอบ: `go test ./...`

หากคำสั่งต่างจาก README เดิม ให้ยึดสคริปต์ของรีพอสิทอรีและเอกสารต้นทางเป็นหลัก ห้าม commit รหัสผ่าน API token กุญแจส่วนตัว หรือการตั้งค่า production ลง Git
