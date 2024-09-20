# Web Scraping with Selenium: Books to Scrape

### Selenium ile Web Kazıma: Kitap Sitesi Kazıma


## Overview / Genel Bakış

This project demonstrates web scraping techniques using Selenium and BeautifulSoup in Python. The target website for scraping is "Books to Scrape," a fictional online bookstore. The primary objective is to extract book details from specific categories like 'Travel' and 'Nonfiction' and store the data in a structured format using Pandas.


Bu proje, Python'da Selenium ve BeautifulSoup kullanarak web kazıma tekniklerini göstermektedir. Kazıma işlemi için hedef site, kurgusal bir çevrimiçi kitapçı olan "Books to Scrape" sitesidir. Projenin ana amacı, 'Travel' ve 'Nonfiction' gibi belirli kategorilerdeki kitapların detaylarını kazıyıp, veriyi Pandas kullanarak yapılandırılmış bir formatta saklamaktır.


## Features / Özellikler

- **Category Scraping:** Extracts book URLs from 'Travel' and 'Nonfiction' categories.
- **Pagination Handling:** Efficiently navigates through paginated content to gather all book data.
- **Book Details Extraction:** Retrieves comprehensive information for each book, including name, price, rating, and description.
- **Data Storage:** Stores the scraped data in a Pandas DataFrame for easy manipulation and analysis.

- **Kategori Kazıma:** 'Travel' ve 'Nonfiction' kategorilerinden kitap URL'lerini çıkarır.
- **Sayfalama İşleme:** Sayfalandırılmış içerikte verimli bir şekilde gezinerek tüm kitap verilerini toplar.
- **Kitap Detayları Kazıma:** Her kitap için ad, fiyat, derecelendirme ve açıklama gibi kapsamlı bilgileri toplar.
- **Veri Saklama:** Kazınan veriyi, kolay manipülasyon ve analiz için Pandas DataFrame içinde saklar.


## Requirements / Gereksinimler

- Python 3.7+
- Selenium
- BeautifulSoup
- Pandas
- Chrome WebDriver


## Usage / Kullanım

1. Initialize the Selenium WebDriver by running the `initialize_driver()` function.
2. Use the `get_travel_and_nonfiction_category_urls()` function to fetch the URLs of the desired categories.
3. Extract all book URLs from the selected categories using the `get_book_urls()` function.
4. Get detailed information for each book using the `get_book_detail()` function.
5. Finally, the data is stored in a Pandas DataFrame, which can be easily exported to a CSV or Excel file for further analysis.

1. Selenium WebDriver'ı `initialize_driver()` fonksiyonu ile başlatın.
2. İstediğiniz kategorilerin URL'lerini almak için `get_travel_and_nonfiction_category_urls()` fonksiyonunu kullanın.
3. Seçilen kategorilerden tüm kitap URL'lerini `get_book_urls()` fonksiyonu ile çıkarın.
4. Her kitap için detaylı bilgileri `get_book_detail()` fonksiyonu ile alın.
5. Son olarak, veri bir Pandas DataFrame'e kaydedilir ve bu veri kolayca CSV veya Excel dosyasına ihraç edilerek daha ileri analizler için kullanılabilir.

