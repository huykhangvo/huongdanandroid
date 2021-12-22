# Hướng dẫn Lập trình Android
Khởi Tạo dự án mới cho người mới bắt đầu
![](https://i0.wp.com/s1.uphinh.org/2021/09/12/image13fc05fc2723b32a.png)

| Function name | Description                    |
| ------------- | ------------------------------ |
| `Name`      | Tên của App cũng như Activity.       |
| `Package name`   | **edu.poly.slide1**     |
| `Save location`   | D:**\LTAndroid\PolyAndroid2021**\slide1demo     |
| `Language`   | **Java(Mình sài java) hoặc Kotlin**     |
| `Minimum SDK`   | **API 28: Android 9.0(Pie)**     |

Ảnh minh họa
![](https://i0.wp.com/s1.uphinh.org/2021/09/12/image51aa01f8d19d849e.png)

Project vừa tạo được lưu ở đây
![](https://i0.wp.com/s1.uphinh.org/2021/09/12/image4fee05b6ad0edad6.png)

Làm quen với giao diện trên Android studio
![](https://i0.wp.com/s1.uphinh.org/2021/09/12/2021-09-12_061701.png)

# Tổng quan về Layout View trong Layout
- ID : Chỉ định tên của View hoặc ViewGroup
- Width: Quy định chiều rộng
- Height: Quy định chiều cao
- Margin: Canh lề giữa các View này với View khác
- Padding: Canh lề chữ bên trong View
- android:id : Là tên được đặt cho Layout (Duy nhất)
- android:foreground : Dùng để chỉ địch màu nền cho Layout đó

# Button

| Các thuộc tính/sự kiện | Mô tả                    |
| ------------- | ------------------------------ |
| `android:id`      | Id của EditText.       |
| `android:layout_width`   | **Độ rộng**     |
| `android:layout_height`      | 	Độ cao       |
| `android:text`      | Chữ hiển thị lên giao diện       |
| `android:textColor`      | Màu chữ       |
| `android:textSize`      | Cỡ chữ       |
| `android:background`      | Màu nền     |
| `android:hint`      | Chữ gợi ý khi android:text rỗng       |
| `android:inputType`      | Thiết lập loại dữ liệu nhập để có bàn phím phù hợp       |
| `android:onClick`      | Gán sự kiện cho Button       |

    <EditText
    android:id="@+id/edtPassword"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:ems="1"
    android:textColor="@android:color/holo_blue_light"
    android:inputType="textPassword"
    android:text="hoilamgi"
     
    />

# ----------------------------------------

    <Button
        android:id="@+id/mybutton_id"
        android:layout_height="wrap_content"
        android:layout_width="220dp"
        android:text="Xin chào"
        android:backgroundTint="#d50000"
        style="@style/Widget.AppCompat.Button.Colored" />
    <Button
        android:layout_height="wrap_content"
        android:layout_width="220dp"
        android:text="Xin chào"
        android:backgroundTint="#9c27b0"
        style="@style/Widget.AppCompat.Button.Colored" />
    <Button
        android:layout_height="wrap_content"
        android:layout_width="220dp"
        android:text="Xin chào"
        android:backgroundTint="#311b92"
        style="@style/Widget.AppCompat.Button.Colored" />
    <Button
        android:layout_height="wrap_content"
        android:layout_width="220dp"
        android:text="Xin chào"
        android:backgroundTint="#00acc1"
        style="@style/Widget.AppCompat.Button.Colored" />
    <Button
        android:layout_height="wrap_content"
        android:layout_width="220dp"
        android:text="Xin chào"
        android:backgroundTint="#00c853"
        style="@style/Widget.AppCompat.Button.Colored" />
    <Button
        android:layout_height="wrap_content"
        android:layout_width="220dp"
        android:text="Xin chào"
        android:backgroundTint="#00c853"
        style="@style/Widget.AppCompat.Button.Colored" />
    <Button
        android:layout_height="wrap_content"
        android:layout_width="220dp"
        android:text="Xin chào"
        android:backgroundTint="#ffd600"
        style="@style/Widget.AppCompat.Button.Colored" />
    <Button
        android:layout_height="wrap_content"
        android:layout_width="220dp"
        android:text="Xin chào"
        android:backgroundTint="#000000"
        style="@style/Widget.AppCompat.Button.Colored" />

