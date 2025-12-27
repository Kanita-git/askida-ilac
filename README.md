# askida-ilac

# Askıda İlaç

Askıda İlaç, ilaç bağışı ve önceliklendirme mantığını simüle eden
Python tabanlı bir konsol uygulamasıdır. Proje, veri yapıları ve
algoritmaların gerçek hayata benzer bir senaryoda kullanımını
göstermek amacıyla geliştirilmiştir.

## Proje Amacı
İlaç verileri bir JSON dosyasından okunur ve kullanıcıya;
arama, sıralama ve önceliklendirme işlemleri sunulur.

## Kullanılan Veri Yapıları
- **Trie**: İlaç isimlerinde hızlı arama
- **Öncelik Kuyruğu (Heap)**: Kritik ilaçların önceliklendirilmesi
- **Sıralama ve Arama Algoritmaları**: Veri düzenleme ve erişim

## Proje Yapısı
askida-ilac/
├── main.py
├── io_utils.py
├── data/
│   └── drugs.json
└── ds/
    ├── heap_pq.py
    ├── sort_search.py
    └── trie.py
