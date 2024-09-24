# FSCalendar

FSCalendar adalah pustaka open-source yang menyediakan tampilan kalender untuk aplikasi iOS. Pustaka ini mendukung berbagai fitur untuk menyesuaikan dan mengintegrasikan kalender sesuai kebutuhan. Dibangun dengan Swift dan Objective-C, FSCalendar memungkinkan pengembang untuk membuat UI kalender yang dinamis dan menarik dengan sedikit usaha.

## Fitur Utama
- **Tampilan Dinamis**: Menyediakan tampilan kalender dalam mode bulanan, mingguan, dan tahunan.
- **Pemilihan Tanggal**: Mendukung pemilihan satu tanggal atau beberapa tanggal sekaligus.
- **Kustomisasi**: Pengembang dapat menyesuaikan tampilan tanggal, warna, gaya, dan lainnya sesuai kebutuhan.
- **Navigasi yang Mudah**: Mendukung navigasi mudah antara bulan dan tahun.
- **Pustaka yang Kompatibel**: Berfungsi baik dengan Swift dan Objective-C.

## Instalasi

### CocoaPods
Untuk menambahkan FSCalendar ke proyek Anda, gunakan `CocoaPods`:
```ruby
pod 'FSCalendar'
```

### Manual
Anda juga bisa mengintegrasikan FSCalendar secara manual dengan menambahkan file dari repositori ini ke dalam proyek Anda.

## Penggunaan Dasar

### Objective-C
```objc
FSCalendar *calendar = [[FSCalendar alloc] initWithFrame:self.view.bounds];
calendar.dataSource = self;
calendar.delegate = self;
[self.view addSubview:calendar];
```

### Swift
```swift
let calendar = FSCalendar(frame: self.view.bounds)
calendar.dataSource = self
calendar.delegate = self
self.view.addSubview(calendar)
```

## Dokumentasi dan Bantuan
Untuk dokumentasi lengkap dan contoh penggunaan, silakan kunjungi halaman [GitHub FSCalendar](https://github.com/WenchaoD/FSCalendar).
