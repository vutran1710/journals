# Event-Loop là gì?

![](.gitbook/assets/event-loop.jpg)

## Giới thiệu

**Event-Loop** là một trong những khái niệm quan trọng nhất của \*JavaScript\*\(JS\), nhưng lại không dễ để hiểu một cách đầy đủ và dễ dàng. Dù đã có vô số bài viết kỹ thuật cố gắng giải thích về Event-loop, nhưng hầu hết đều khó tiếp cận \(bất đồng ngôn ngữ, cách diễn đạt, mức độ sâu sắc của người viết…\).

Bài viết này cố gắng cung cấp một lời giải thích ngắn gọn và dễ hình dung, nhưng đi từ cốt lõi vấn đề cũng như những yếu tố xung quanh cần lưu tâm khi lập trình với Event-Loop nói riêng và JS nói chung. Để đảm bảo tính dễ hiểu, bài viết giả định người đọc chỉ có những kiến thức cơ bản nhất về lập trình với JavaScript.

Do hạn chế về kiến thức và thời gian của người viết, mọi ý kiến đóng góp sửa chữa đều được hoan nghênh.

Bài viết được lưu tại:

1. discord channel **vietnam**
2. [http://journal.vutr.io](http://journal.vutr.io)

## Tổng quát

Tham khảo: [MDN Official: EventLoop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)

Trước tiên để hiểu về Event-Loop, trước hết ta cần hiểu một số khái niệm cơ bản nhất của máy tính và lập trình, bao gồm Stack, Queue, RAM.

### 

