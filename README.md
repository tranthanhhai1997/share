Repo Cầu nối để tạo video hàng loạt từ VEO3, Muse (mình sẽ bổ sung seedance sau)
Kinh nghiệm + mã tham chiếu để tạo và tải ảnh / video AI hàng loạt từ:
Google Flow: Veo 3 (text→video, ảnh→video theo ảnh tham chiếu) + tạo ảnh
Muse (muse.ai của Meta): ảnh + ảnh→video
ChatGPT: tạo ảnh (chế độ UI hoặc backend-api, có đính ảnh mẫu); hỏi text để viết prompt hàng loạt
Gemini: hỏi text
Grok: grok.com/imagine (web) và xAI API chính thức
https://github.com/tranthanhhai1997/ai-media-batch-kit
--------------
Repo Giọng đọc (TTS) miễn phí / giá rẻ cho app, kèm kinh nghiệm thực chiến. Phần tiếng Việt được chú trọng riêng.
chuẩn hoá chữ tiếng Việt: số, ngày, giờ, tiền, %, đơn vị;
lồng tiếng nhiều nhân vật: tách lời dẫn/lời thoại, chọn giọng theo giới tính/tuổi, nghỉ khi đổi người nói;
phụ đề SRT/VTT theo mốc từng từ, căn lại theo chữ gốc.
https://github.com/tranthanhhai1997/ai-voice-free-kit (Còn repo sử dụng hơn 9000 voice ngoại elevenlabs free ai cần thì ib riêng mình nhé, cái này không share free và không public được)
--------------
Repo check Music Copyright & Re-upload Hunter 🛡️🎵
Hệ thống tự động quét và phát hiện các video vi phạm bản quyền / re-upload nhạc trái phép trên YouTube bằng thuật toán nhận dạng dấu vân tay âm thanh Chroma-12 FFT Audio Fingerprinting.
https://github.com/tranthanhhai1997/music-copyright-hunter
--------------
Suno Master Cheatsheet & Prompt Builder (v5 / v6) 🎵✨
Bộ công cụ tự động hóa sáng tác thơ vần điệu & xây dựng cấu trúc Prompt nhạc cho Suno AI (tối ưu toàn diện cho các phiên bản v5, v5.5, v6, v6-wild, v6-mini - đã lược bỏ các quy tắc cũ của v4.5).
https://github.com/tranthanhha.../suno-master-prompt-builder
--------------
AI Video Downloader, Translator & Auto-Dubbing Pipeline 🎬🇻🇳
Tải video chất lượng cao không logo/watermark từ đa nền tảng: Douyin (抖音), TikTok, YouTube (Shorts & Long), Facebook Reels, Bilibili, Kuaishou (快手), Instagram, X/Twitter.
Quy trình tự động Việt hóa & lồng tiếng thông minh (End-to-End Dubbing): Tách tiếng (ASR Whisper) ➔ Dịch thuật ngữ cảnh video (AI Translator) ➔ Tạo giọng lồng tiếng ElevenLabs miễn phí (Voice Synthesis) ➔ Tự động co giãn tốc độ (Atempo time-stretching) ➔ Giảm âm lượng nhạc nền (Audio Ducking) ➔ Xuất video hoàn thiện kèm Vietsub!
https://github.com/tranth.../ai-video-translator-and-dubbing
--------------
Auto-Karaoke Maker 🎤✨
Hệ thống tự động biến bất kỳ bài hát nào thành Video Karaoke chuyên nghiệp với chữ chạy highlight đổi màu từng nốt ngân chuẩn xác như phòng hát dịch vụ!
🌟 Quy trình 4 bước hoàn toàn tự động
Tách Vocal & Beat sạch sẽ: Sử dụng AI Demucs v4 của Meta để tách hoàn toàn giọng ca sĩ khỏi beat gốc, tạo ra bản nhạc nền karaoke (instrumental.wav) chất lượng phòng thu.
Căn lời siêu chuẩn mili-giây (Word-level Forced Alignment): Dùng AI nhận diện chính xác từng từ bắt đầu khi nào và nốt ngân kéo dài bao lâu (start_time, end_time, duration).
Sinh phụ đề Karaoke chuẩn quốc tế (.ass & .lrc): Tự động sinh file SubStation Alpha với thẻ {\\k<centiseconds>} đổi màu chữ từ trắng sang vàng/cyan theo đúng nhịp hát của ca sĩ.
Dựng Video Karaoke MP4 1080p bằng FFmpeg: Ghép beat nhạc + video/ảnh nền + phụ đề karaoke chạy chữ thành video MP4 sắc nét, sẵn sàng upload YouTube hoặc mở hát trên TV!
https://github.com/tranthanhhai1997/auto-karaoke-maker
-----
1 vài tool mình đã làm và đang kiếm tiền từ nó
Tool sản xuất video: https://autocine.vn-tool.online
Tool làm nhạc AI: https://melodai.vn-tool.online/
Tool làm video giáo dục: https://aiedu.vn-tool.online/
----
Tiện thể anh muốn học vibe code tool chưa có kinh nghiệm thì mình sẵn sàng nhận đệ tử kèm 1:1 đến khi đủ lông đủ cánh tự bay được (ưu tiên người trẻ, có kinh nghiệm về cntt 1 chút)
