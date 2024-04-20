# STM32-use-FreeRTOS-task-and-queue-UART
Dùng FreeRTOS STM32 giao tiếp 1 nút nhấn, một LED và giao tiếp máy tính qua UART. Nếu nút nhấn được nhấn, thì LED được đảo trạng thái.Khi nhả nút LED giữ nguyên trạng thái UART gửi các command sau: làm LED sáng  làm LED tắt làm LED đảo trạng thái 3 task thông tin với nhau qua queue và mỗi task giao tiếp với 1 thiết bị button, LED, UART.
