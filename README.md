# Entry_Level-Job_scraper
"Automated job scraping and analysis tool for 'No Experience Required' jobs from Stanby. It automatically filters ads, classifies work styles (Remote/Commute), and extracts salary info into a clean CSV."
# Stanby Job Scraper & Analyzer

## 概要
スタンバイ（Stanby）から「未経験OK」求人リストをスクレイピングし、分析しやすい形式に自動整形するツールです。

## 主な機能
- **自動フィルタリング**: 広告リンクを除外し、純粋な求人ページのみを抽出。
- **データ分析**: タイトルから「在宅/リモート」「通勤」を自動分類。
- **給与抽出**: タイトルから給与情報を抜き出し、分析用CSVとして出力。

## 使い方
1. スタンバイから検索結果URLリストを `未経験OK_jobs.csv` として保存。
2. Google Colab上でスクリプトを実行。
3. `整理済み_求人リスト.csv` が自動でダウンロードされます。

## 使用技術
- Python
- Pandas (データ加工)
- BeautifulSoup (スクレイピング)
- Requests (データ取得)
