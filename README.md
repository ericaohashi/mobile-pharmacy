# README

## usersテーブル
| Column             |Type    |Options                   |
|--------------------|--------|--------------------------|
| last_name          | string | null: false              |
| first_name         | string | null: false              |
| last_kana          | string | null: false              |
| first_kana         | string | null: false              |
| encrypted_password | string | null: false              |
| email              | string | null: false,unique: true |
| nickname           | string | null: false              |
| birth              | date   | null: false              |

## medicine テーブル

| Column             |Type    |Options                   |
|--------------------|--------|--------------------------|
| japanese_name      | string | null: false              |
| english_name       | string | null: false              |
| effect             | string | null: false              |
| dose               | string | null: false              |
| ingredient         | string | null: false              |
| category           | integer| null: false              |
| symptom_id         | integer| null: false              |
| smiler_medicine    | string | null: false              |
| price              | integer| null: false              |


## talk テーブル
| Column             |Type    |Options                   |
|--------------------|--------|--------------------------|
| comment            | string | null: false              |
| user               | string | null: false              |

## usr_symptom テーブル
| Column             |Type    |Options                   |
|--------------------|--------|--------------------------|
| side_effect        | string |                          |
| combination        | string |                          |
| history            | string |                          |
| current            | string |                          |
| allergy            | string |                          |
| pregnancy_id       | integer|                          |
| age                | integer|                          |
|