# Quy trình tích hợp OSM (ngoài trời) với dữ liệu tòa nhà nội khu (indoor) để tìm đường liền mạch từ ngoài → vào tòa nhà → tới từng phòng.
  <img width="435" height="371" alt="Image" src="https://github.com/user-attachments/assets/f75f7ef6-4fe0-4dd9-bca8-e1c8ae3d6be7" />

  ## Bước 1 – Import OSM Việt Nam vào PostGIS → tạo graph routing ngoài trời
  vietnam-latest.osm.pbf

  
  | Lớp             | Ví dụ                     |
| --------------- | ------------------------- |
| **phong**       | Phòng học, phòng họp      |
| **hanh_lang**   | Hành lang, lối đi         |
| **loi_ra**      | Cửa, thang                |
| **nut_ket_noi** | Điểm nối indoor ↔ outdoor |

