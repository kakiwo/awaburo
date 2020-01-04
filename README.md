# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## userテーブル

|Column|Type|Options|
|------|----|-------|
|avatar_image_id|integer|null: false, foreign_key: true|
|biography|string|null: false, foreign_key: true|
|last_name|string|null: false, foreign_key: true|
|first_name|string|null: false, foreign_key: true|
|last_name_kana|string|null: false, foreign_key: true|
|first_name_kana|string|null: false, foreign_key: true|
|postcode|string|null: false, foreign_key: true|
|city|string|null: false, foreign_key: true|
|block|string|null: false, foreign_key: true|
|building|string|null: false, foreign_key: true|
|phone_number|string|null: false, foreign_key: true|
|is_phone_number_authenticated|string|null: false, foreign_key: true|
|credit|string|null: false, foreign_key: true|
|email|string|null: false, foreign_key: true|
|password|string|null: false, foreign_key: true|

### Association
- has_many :items