NBAIF NÂNG CAO ĐÃ LÀM: 

NC1	Xin hai quyền cùng lúc và xử lý từng quyền riêng.	ActivityResultContracts.RequestMultiplePermissions() — callback nhận Map<String, Boolean>.

NC3	Bấm vào thông báo thì mở lại app.	PendingIntent.getActivity(...) + setContentIntent(...) với cờ FLAG_IMMUTABLE.
