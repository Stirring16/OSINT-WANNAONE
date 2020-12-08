 #  OSINT-WANNAONE
![screenshoot](https://camo.githubusercontent.com/3e97657a37857065d6ad5935e4f1d4dc629209f460edf8c643d45281021dba2c/68747470733a2f2f636e73632e7569742e6564752e766e2f626c6f672f6d656469612f323032302f30362f556e7469746c65642d312e706e67)
> ## Authur: St1rr1ng

 ## WHAT IS OSINT?
* [OSINT](https://en.wikipedia.org/wiki/Open-source_intelligence) là 1 cụm viêt tắt cho Open Source Intelligency. Trong đó Open Source hay còn gọi là những nguồn mở được public trên internet và Intelligency là Tình báo (sự thu thập các tin tức). Từ đó ta có thể hiểu được là đây chính là những phương thức, cách thức khai thác lấy những thông tin từ video, hình ảnh, văn bản,.. từ những gì liên quan đến mục tiêu có sẵn và đang public trên internet. Những nguồn đó có thể ở bất cứ đâu : trên forum, trên các trang báo, trong 1 cuốn sách, video hay là những thư viện mở, các báo cáo và lịch sử từ trước đó.

## OSINT FRAMEWORK
* Một nơi tuyệt vời để bắt đầu là OSINT Framework do Justin Nordine tổng hợp lại. The Framework cung cấp các liên kết đến một bộ sưu tập lớn tài nguyên cho nhiều tác vụ khác nhau, từ thu thập địa chỉ email đến tìm kiếm trên mạng xã hội hoặc web đen.
* > https://osintframework.com/
![screenshoot](https://www.sentinelone.com/wp-content/uploads/2019/07/osint-fw.jpg)

## OSINT TOOLS
* [Google](https://www.google.com/) là một công cụ tìm kiếm tuyệt vời và là công cụ được sử dụng tìm kiếm nhiều nhất.
![screenshoot](https://community99.com/wp-content/uploads/2020/10/ot-contrib-google.png)
* [GooleDork](https://whitehat.vn/threads/gioi-thieu-google-dork.5629/) là một chức năng mà google cung cấp để việc tìm kiếm hiệu quả hơn. 
![screenshoot](https://geekflare.com/wp-content/uploads/2019/08/Capture3.png)
* [Shodan](https://www.shodan.io/) cũng là một công cụ tìm kiếm như Google nhưng nó sẽ mang lại các kết quả ý nghĩa và liên quan đến bảo mật hơn. Tools OSINT này chủ yếu giúp nhà phân tích bảo mật xác định mục tiêu và kiểm tra các lỗ hổng, mật khẩu, dịch vụ, cổng khác nhau,.v.v.
![screenshoot](https://miro.medium.com/max/489/0*A0ikOtR7_yyMtfV6)
* [Spyse](https://spyse.com/) cung cấp dữ liệu khổng lồ để khám phá mục tiêu thông qua các điểm vào khác nhau
![screenshoot](https://hackernoon.com/drafts/tm1to3yyi.png)
 
### Đây chỉ là mốt số ít công cụ mà mình đã từng sử dụng để giải các Challenge Osint. Dưới đây là một số Link với đầy đủ các công cụ tìm kiếm cho mỗi vấn đề mà bạn gặp: 
 * https://github.com/jivoi/awesome-osint#-dns
 * https://geekflare.com/osint-tools/ 
 * [Trang này tuyệt vời lắm :D](https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf)
 * https://medium.com/the-first-digit/osint-how-to-find-information-on-anyone-5029a3c7fd56
 * https://www.randhome.io/blog/2019/01/05/2019-osint-guide/
 
 ## Một số trang web luyện tập OSINT và WriteUp hay.
 * [Cyber Space](https://www.facebook.com/cyberg0100): CyberSpace thường xuyên đưa ra các Challenge rất thực tế trên trang Facebook của họ.
 * https://medium.com/week-in-osint
 * https://www.linkedin.com/pulse/trendmicro-ctf-2017-osint-challenge-write-up-motasem-hamdan/ 
 *  https://www.digital.security/en/blog/write-defcon-25-recon-village-osint-ctf
 * https://stormctf.ninja/ctf/blog/stormctf/bellebytes-osint-guide
 * https://exploit.studio/wp-content/uploads/2019/07/ExploitStudio_SpyingChallenge_2019_Stage1_Report.pdf
 * https://spyingchallenge.com/wp-content/uploads/2019/02/WriteUp_Spying_Challenge_2018_ENG.pdf
 * https://cyberlances.wordpress.com/2020/10/12/cyber-space-osint-challenge-53-writeup/?fbclid=IwAR00pzwx__UhvSDE7v-xUZuuvz1Gl_nqz66WRyEuTeAdVj0pG6xDXVKvYbo
 
 ## Sau đây mình sẽ Write Up một số bài đơn giản của CyberSpace mà mình đã giải được để các bạn có thể hiểu được cách chơi hệ OSINT này nhé. Ok Let's go
 
 # 1. 
> [OSINT Challenge](https://www.facebook.com/cyberg0100/photos/a.463498964223106/873807879858877/): Tìm ra nơi tác giả đứng để chụp tấm ảnh này? Gửi kết quả dưới dạng LAT, LONG hoặc Link Google Maps trực tiếp đến địa điểm.
 ![screenshoot](https://scontent.fsgn2-6.fna.fbcdn.net/v/t1.0-9/130282602_873807883192210_2736500427402058534_o.jpg?_nc_cat=100&ccb=2&_nc_sid=730e14&_nc_ohc=7aAsaMP086EAX-nXn5H&_nc_ht=scontent.fsgn2-6.fna&oh=d73bff9e7cd1337acd0d8b4e88a97be0&oe=5FF59540)
 
 Đầu tiên mình ```Search the web for image``` sau đó mình tìm thông tin về bức ảnh với từ khóa ```buiding```
 
 ![screenshoot](https://i.imgur.com/tzgoekb.png)
 
 Sau khi tìm kiếm không khả thi, mình nhìn lại xem trên bức ảnh có gì đặc biệt không. Nhìn bức ảnh các bạn sẽ thấy tòa nhà nhiều với 3 màu cam, xanh trắng mình liền search google với key ```orange, green, white buiding```
 Sau đó mình tìm được một bài viết có hình giống như tòa nhà giống mình tìm kiếm: https://www.stanhopeplc.com/projects/central-saint-giles
 
 ![screenshoot](https://i.imgur.com/DpLiGyS.png)
 
 Sau khi đọc ta có được thông tin địa chỉ tòa nhà ```The building provides a new public plaza for the Tottenham Court Road area, and is home to one of Google’s London offices.```
 Search google map key ```Tottenham Court Road area``` dưới chế độ ```Satelline``` tìm kiếm tòa nhà và góc tác giả đứng chụp. Bấm vào tòa nhà tác giả đứng chụp và ta có đáp án là: ```51.51730173654459, -0.12462196379354945```
 
 ![screenshoot](https://i.imgur.com/5ruVlnZ.png)  
 
 
 # 2. Một bài khá hay từ anh ```th4nl4n_k1d13u``` của Cyber Space
> OSINT Challenge #53:

```siMPSIMpSIMpsiMPSImpSiMpsIMpSiMpsimpSimpSiMPsIMPSImpSImPSImPSImpSiMpsimpSimPSImpSimPSiMPSIMPsImpsiMPsiMPsImPSimpSiMPSImpsiMpSImPsimPSIMPSImpSIMpsImpsiMPSimPSimPSImpSimpSImPSiMPSiMpSImpsiMpSimpSimPSimPsImpSimPsiMPSimPsIMPSIMPsiMpsImpsimPSiMPsImPsIMPSimpSiMPsIMPsIMpSiMpsiMPsIMpsImPSimpsiMPsIMpSIMPsiMpsIMPSImPSIMPSIMPSIMpsImPsImpsiMpsiMpsImpsIMPSiMPSIMPsiMpsIMpsImPSiMPsImPSImpsimPSiMPSImPSiMpsIMpsiMPsiMPsiMpSimPsiMPsIMpSIMPsIMPsImPSiMPsIMpSimPSiMPsImpSiMpSIMPsImpsImpsimpsiMpSiMPsIMpSIMPSimpsimPSImPSImPSImPsImPSImPSiMPSImpsimPSImpsimpSimpsiMpSimPsimPSimpsIMPsimpSImpsiMpSimpSImpsiMPsIMPSIMpsImPsiMPsiMpsimPsImpSimPSIMPSiMpsImpsiMPsiMpSiMpSimpSimpSIMpsiMpsImPSImPsimpsiMPsimPSImpSiMPSImpSIMpSImpSiMpsIMPsiMPsImpSimpSImPsIMPsImpSiMPsiMPsImPsimPSiMpsimpsImPSIMPsImPSimpSIMpSIMpsImpsimPsimpSiMPSImPsIMpsiMpSIMPsiMPsiMpSIMpsImPsIMPSimPsImPSiMpSiMPsIMPSImPSimpSimPSIMpSimpSImpsimpSIMpSIMppsImpsiMPsiMpSiMpSimpSimpSIMpsiMpsImPSImPsimpsiMPsimPSImpSiMPSImpSIMpSImpSiMpsIMPsiMPsImpSimpSImPsIMPsImpSiMPsiMPsImPsimPSiMpsimpsImPSIMPsImPSimpSIMpSIMpsImpsimPsimpSiMPSImPsIMpsiMpSIMPsiMPsiMpSIMpsImPsIMPSimPsImPSiMpSiMPsIMPSImPSimpSimPSIMpSimpSImpsimpSIMpSIMpSImPsimpsIMpSImPsImpsimPSImpSIMPSimPSIMPSimpsimPsimpSIMPSImPsIMpSIMpSiMpSiMPsIMpsIMPSiMpSiMPSImpsiMPSiMpsiMPSIMPsIMpSImpSIMpSIMpSimpSimPsIMpSimpSImpSimPSiMpSimPsiMPsIMPsImpSimpsImPsIMPsIMPSIMpSIMPsimPSIMPsiMPSImpSImpSIMPSiMPsIMpsImpSimPSImpsIMPSImPsImpsImPSImPSImPSImpsiMpSIMPSImpSImpsimPsiMPSIMpsiMpsIMpSiMPsiMPsIMPsimPsIMpSimPSImPsIMpsiMpsIMpsiMpSimpSiMpsIMPSimpsIMPSIMPSiMPsImPSimpsimpsimPSImpsImpSIMpsimPsimpsimpsimpsImpSimpSiMpsimpSiMpsIMpSImPsIMpsImpSImpsimpSiMPsimPSIMPSIMpsimPsImpSImPSiMPSiMpSiMpSiMPSIMPsiMpSimPsiMpSimPSimPsimPsIMPSiMPSImPSImPsimpSimpSiMPsImPsiMpsiMPSImPsiMpsiMPSiMpSImpSimpsIMpsimpSiMpSIMPSiMPSiMPsimPSIMpSIMPSiMPSIMPsimPSiMPsimpsIMPsImPSimPsIMPsIMPSImpSIMPsIMPsiMpSIMPsimPsiMPSiMpSIMpSimPSImpSImpsiMpsiMpSImpSIMpsimpsIMPSIMpsimpSIMpSImpsimPSimPsiMpsiMPsimPsImPsIMpSIMPsImPsIMPSimPsimPsImpSimpsimPsIMpSImPsiMPSiMpSImPSiMpsimPsIMpSimpSiMPsImPsiMPsImpsIMPSiMpSIMPSimPSIMPSImpsImpsIMpsIMpsIMPsIMPSiMPSIMpsImpsImPsImPSImpSimpsImPSiMPSimPsImPSIMPSiMPSimpSImpsImpSimPSimPSiMPSImpSimPsimPsImpsIMPSIMPsimPsIMPsImPsIMPsImpSimPSImPsimpSImPSiMPSImPSImpSiMpSImPSimPsimPSImpSIMpsIMpsimPsimpsIMPsiMPSIMPSIMPSIMpsImpsImPSiMPSimpsIMPsIMPSImpsIMPsiMpsiMPSImpsiMPsImPsimPSiMPSImPSIMPSImPSImPsIMpSIMPSIMPSiMPsiMpSiMPSimPSIMpSimPSImpSIMPsimpsimPSimpSImPSimpSimPSIMpsImpsiMpsimpsiMPsIMpSIMPsImPSimpsiMpsiMpsIMpsImPSiMPSIMPsImpsIMpSIMPsImpsImPsIMpsImpSIMpSImPSIMPSimPSIMPsiMpsiMPsimPSImpsimPSIMpSIMPsimPsIMpsIMpsIMPSimpsIMPsImPSiMpsImpSimpSImPsImpsimpsimPSImPsIMpSIMpsImpsIMPsImpSiMpsImpsiMpsiMpSiMpSImpsiMPsImPSImpsimPsimpsIMPsimPSImpsimPSIMPsiMPSimPSiMPSiMpsIMpSiMpSImPsiMpSIMPSIMpsImpsimpsimpsimpSiMPsiMPsIMPsimpSIMpSIMPSimPsIMpsIMpsImPSimpsIMpSImPsimPsIMPSIMpsimpsimPsImpsimpsImPsImPsimpsiMPSIMPsIMpSiMpSImPsImPsImPsImPsimPSImpsImpsimpsimpSiMpsiMPsiMPsiMpSimPSImpSIMPsIMPSimPsIMpSIMpsiMpSIMpsIMpsimpSIMpSimpsImPsIMpsImpsImPSImPsiMpsiMPSImPSimpSimpSiMPSimPSImPSimpsiMpsIMpsImPsImpSImPsIMPsImPsimpsimPSIMpSimPsImPsiMpSiMpSiMpSIMpsiMpSiMPsimpsImpSiMpSiMPsImPSiMPSimPSIMPsimPsimPsImPsIMpSiMpSiMpsIMpsiMpSimpSimpsiMPSimPsIMPSimpSImpSIMPsiMPSIMPsimpSIMpsiMpSiMpsimPSiMPSimpsImpSimpsiMPsimPsimpsImpSiMpsimpsimPSimpsiMpsIMPSimpsimPSIMPSIMpSiMPsiMPSImPSImPsIMpsImpSiMpSIMpSimpSimPsimPSiMPSimpSiMpSimPSIMPSiMpsIMPsImPSimPSImPsImPsiMPsiMPsIMpSIMpSiMPSimpsiMPsIMPsImPSImPsIMPsImpSiMPsimpSImpSiMpSimPsimPSImPsImpsIMpSimPsiMpSimPSimPSimPSimpSIMpsIMPSImpSIMPsImpsimPSImpsimPSimpSIMPsiMpsiMpsimpsIMpSImpsiMpSIMPSimpSiMPSiMPsIMpSiMpsiMpSimPSimpsimpSimpsImpSiMpsImpSImPsiMpsiMpSimpsiMPSIMpsIMpsimpsIMPSimPSImPSiMPSiMpSIMPsIMpsIMpsiMpsImPsimPsImPsimpsimpsImPsimpsIMPsiMpSiMPSimPsimPsIMpsiMpsIMpsiMPSIMpsIMpSImPsimPSIMpSimPSIMpsiMpSImpSiMPsimpsimpSImPsImpSimPsimpsIMPsImPsiMPSIMpsiMPSIMPSimpSIMPsiMPSimPSiMpsimPsimPSimpSImpsImPsimpSiMpsImPsImpsiMpsimpSimPsiMpSImpsimPsimPsimpsimpsImpsimpSimPsImPSiMpSIMpSiMpsIMpsIMpSiMpSimpsImPSImPsimpsIMpSImPsImpsimPSImpSIMPSimPSIMPSimpsimPsimpSIMPSImPsIMpSIMpSiMpSiMPsIMpsIMPSiMpSiMPSImpsiMPSiMpsiMPSIMPsIMpSImpSIMpSIMpSimpSimPsIMpSimpSImpSimPSiMpSimPsiMPsIMPsImpSimpsImPsIMPsIMPSIMpSIMPsimPSIMPsiMPSImpSImpSIMPSiMPsIMpsImpSimPSImpsIMPSImPsImpsImPSImPSImPSImpsiMpSIMPSImpSImpsimPsiMPSIMpsiMpsIMpSiMPsiMPsIMPsimPsIMpSimPSImPsIMpsiMpsIMpsiMpSimpSiMpsIMPSimpsIMPSIMPSiMPsImPSimpsimpsimPSImpsImpSIMpsimPsimpsimpsimpsImpSimpSiMpsimpSiMpsIMpSImPsIMpsImpSImpsimpSiMPsimPSIMPSIMpsimPsImpSImPSiMPSiMpSiMpSiMPSIMPsiMpSimPsiMpSimPSimPsimPsIMPSiMPSImPSImPsimpSimpSiMPsImPsiMpsiMPSImPsiMpsiMPSiMpSImpSimpsIMpsimpSiMpSIMPSiMPSiMPsimPSIMpSIMPSiMPSIMPsimPSiMPsimpsIMPsImPSimPsIMPsIMPSImpSIMPsIMPsiMpSIMPsimPsiMPSiMpSIMpSimPSImpSImpsiMpsiMpSImpSIMpsimpsIMPSIMpsimpSIMpSImpsimPSimPsiMpsiMPsimPsImPsIMpSIMPsImPsIMPSimPsimPsImpSimpsimPsIMpSImPsiMPSiMpSImPSiMpsimPsIMpSimpSiMPsImPsiMPsImpsIMPSiMpSIMPSimPSIMPSImpsImpsIMpsIMpsIMPsIMPSiMPSIMpsImpsImPsImPSImpSimpsImPSiMPSimPsImPSIMPSiMPSimpSImpsImpSimPSimPSiMPSImpSimPsimPsImpsIMPSIMPsimPsIMPsImPsIMPsImpSimPSImPsimpSImPSiMPSImPSImpSiMpSImPSimPsimPSImpSIMpsIMpsimPsimpsIMPsiMPSIMPSIMPSIMpsImpsImPSiMPSimpsIMPsIMPSImpsIMPsiMpsiMPSImpsiMPsImPsimPSiMPSImPSIMPSImPSImPsIMpSIMPSIMPSiMPsiMpSiMPSimPSIMpSimPSImpSIMPsimpsimPSimpSImPSimpSimPSIMpsImpsiMpsimpsiMPsIMpSIMpsImpsiMPsiMpSiMpSimpSimpSIMpsiMpsImPSImPsimpsiMPsimPSImpSiMPSImpSIMpSImpSiMpsIMPsiMPsImpSimpSImPsIMPsImpSiMPsiMPsImPsimPSiMpsimpsImPSIMPsImPSimpSIMpSIMpsImpsimPsimpSiMPSImPsIMpsiMpSIMPsiMPsiMpSIMpsImPsIMPSimPsImPSiMpSiMPsIMPSImPSimpSimPSIMpSimpSImpsimpSIMpSIMpSImPsimpsIMpSImPsImpsimPSImpSIMPSimPSIMPSimpsimPsimpSIMPSImPsIMpSIMpSiMpSiMPsIMpsIMPSiMpSiMPSImpsiMPSiMpsiMPSIMPsIMpSImpSIMpSIMpSimpSimPsIMpSimpSImpSimPSiMpSimPsiMPsIMPsImpSimpsImPsIMPsIMPSIMpSIMPsimPSIMPsiMPSImpSImpSIMPSiMPsIMpsImpSimPSImpsIMPSImPsImpsImPSImPSImPSImpsiMpSIMPSImpSImpsimPsiMPSIMpsiMpsIMpSiMPsiMPsIMPsimPsIMpSimPSImPsIMpsiMpsIMpsiMpSimpSiMpsIMPSimpsIMPSIMPSiMPsImPSimpsimpsimPSImpsImpSIMpsimPsimpsimpsimpsImpSimpSiMpsimpSiMpsIMpSImPsIMpsImpSImpsimpSiMPsimPSIMPSIMpsimPsImpSImPSiMPSiMpSiMpSiMPSIMPsiMpSimPsiMpSimPSimPsimPsIMPSiMPSImPSImPsimpSimpSiMPsImPsiMpsiMPSImPsiMpsiMPSiMpSImpSimpsIMpsimpSiMpSIMPSiMPSiMPsimPSIMpSIMPSiMPSIMPsimPSiMPsimpsIMPsImPSimPsIMPsIMPSImpSIMPsIMPsiMpSIMPsimPsiMPSiMpSIMpSimPSImpSImpsiMpsiMpSImpSIMpsimpsIMPSIMpsimpSIMpSImpsimPSimPsiMpsiMPsimPsImPsIMpSIMPsImPsIMPSimPsimPsImpSimpsimPsIMpSImPsiMPSiMpSImPSiMpsimPsIMpSimpSiMPsImPsiMPsImpsIMPSiMpSIMPSimPSIMPSImpsImpsIMpsIMpsIMPsIMPSiMPSIMpsImpsImPsImPSImpSimpsImPSiMPSimPsImPSIMPSiMPSimpSImpsImpSimPSimPSiMPSImpSimPsimPsImpsIMPSIMPsimPsIMPsImPsIMPsImpSimPSImPsimpSImPSiMPSImPSImpSiMpSImPSimPsimPSImpSIMpsIMpsimPsimpsIMPsiMPSIMPSIMPSIMpsImpsImPSiMPSimpsIMPsIMPSImpsIMPsiMpsiMPSImpsiMPsImPsimPSiMPSImPSIMPSImPSImPsIMpSIMPSIMPSiMPsiMpSiMPSimPSIMpSimPSImpSIMPsimpsimPSimpSImPSimpSimPSIMpsImpsiMpsimpsiMPsIMpSIMPsImPSimpsiMpsiMpsIMpsImPSiMPSIMPsImpsIMpSIMPsImpsImPsIMpsImpSIMpSImPSIMPSimPSIMPsiMpsiMPsimPSImpsimPSIMpSIMPsimPsIMpsIMpsIMPSimpsIMPsImPSiMpsImpSimpSImPsImpsimpsimPSImPsIMpSIMpsImpsIMPsImpSiMpsImpsiMpsiMpSiMpSImpsiMPsImPSImpsimPsimpsIMPsimPSImpsimPSIMPsiMPSimPSiMPSiMpsIMpSiMpSImPsiMpSIMPSIMpsImpsimpsimpsimpSiMPsiMPsIMPsimpSIMpSIMPSimPsIMpsIMpsImPSimpsIMpSImPsimPsIMPSIMpsimpsimPsImpsimpsImPsImPsimpsiMPSIMPsIMpSiMpSImPsImPsImPsImPsimPSImpsImpsimpsimpSiMpsiMPsiMPsiMpSimPSImpSIMPsIMPSimPsIMpSIMpsiMpSIMpsIMpsimpSIMpSimpsImPsIMpsImpsImPSImPsiMpsiMPSImPSimpSimpSiMPSimPSImPSimpsiMpsIMpsImPsImpSImPsIMPsImPsimpsimPSIMpSimPsImPsiMpSiMpSiMpSIMpsiMpSiMPsimpsImpSiMpSiMPsImPSiMPSimPSIMPsimPsimPsImPsIMpSiMpSiMpsIMpsiMpSimpSimpsiMPSimPsIMPSimpSImpSIMPsiMPSIMPsimpSIMpsiMpSiMpsimPSiMPSimpsImpSimpsiMPsimPsimpsImpSiMpsimpsimPSimpsiMpsIMPSimpsimPSIMPSIMpSiMPsiMPSImPSImPsIMpsImpSiMpSIMpSimpSimPsimPSiMPSimpSiMpSimPSIMPSiMpsIMPsImPSimPSImPsImPsiMPsiMPsIMpSIMpSiMPSimpsiMPsIMPsImPSImPsIMPsImpSiMPsimpSImpSiMpSimPsimPSImPsImpsIMpSimPsiMpSimPSimPSimPSimpSIMpsIMPSImpSIMPsImpsimPSImpsimPSimpSIMPsiMpsiMpsimpsIMpSImpsiMpSIMPSimpSiMPSiMPsIMpSiMpsiMpSimPSimpsimpSimpsImpSiMpsImpSImPsiMpsiMpSimpsiMPSIMpsIMpsimpsIMPSimPSImPSiMPSiMpSIMPsIMpsIMpsiMpsImPsimPsImPsimpsimpsImPsimpsIMPsiMpSiMPSimPsimPsIMpsiMpsIMpsiMPSIMpsIMpSImPsimPSIMpSimPSIMpsiMpSImpSiMPsimpsimpSImPsImpSimPsimpsIMPsImPsiMPSIMpsiMPSIMPSimpSIMPsiMPSimPSiMpsimPsimPSimpSImpsImPsimpSiMpsImPsImpsiMpsimpSimPsiMpSImpsimPsimPsimpsimpsImpsimpSimPsImPSiMpSIMpSiMpsIMpsIMpSiMpSimpsImPPsImPSimpsiMpsiMpsIMpsImPSiMPSIMPsImpsIMpSIMPsImpsImPsIMpsImpSIMpSImPSIMPSimPSIMPsiMpsiMPsimPSImpsimPSIMpSIMPsimPsIMpsIMpsIMPSimpsIMPsImPSiMpsImpSimpSImPsImpsimpsimPSImPsIMpSIMpsImpsIMPsImpSiMpsImpsiMpsiMpSiMpSImpsiMPsImPSImpsimPsimpsIMPsimPSImpsimPSIMPsiMPSimPSiMPSiMpsIMpSiMpSImPsiMpSIMPSIMpsImpsimpsimpsimpSiMPsiMPsIMPsimpSIMpSIMPSimPsIMpsIMpsImPSimpsIMpSImPsimPsIMPSIMpsimpsimPsImpsimpsImPsImPsimpsiMPSIMPsIMpSiMpSImPsImPsImPsImPsimPSImpsImpsimpsimpSiMpsiMPsiMPsiMpSimPSImpSIMPsIMPSimPsIMpSIMpsiMpSIMpsIMpsimpSIMpSimpsImPsIMpsImpsImPSImPsiMpsiMPSImPSimpSimpSiMPSimPSImPSimpsiMpsIMpsImPsImpSImPsIMPsImPsimpsimPSIMpSimPsImPsiMpSiMpSiMpSIMpsiMpSiMPsimpsImpSiMpSiMPsImPSiMPSimPSIMPsimPsimPsImPsIMpSiMpSiMpsIMpsiMpSimpSimpsiMPSimPsIMPSimpSImpSIMPsiMPSIMPsimpSIMpsiMpSiMpsimPSiMPSimpsImpSimpsiMPsimPsimpsImpSiMpsimpsimPSimpsiMpsIMPSimpsimPSIMPSIMpSiMPsiMPSImPSImPsIMpsImpSiMpSIMpSimpSimPsimPSiMPSimpSiMpSimPSIMPSiMpsIMPsImPSimPSImPsImPsiMPsiMPsIMpSIMpSiMPSimpsiMPsIMPsImPSImPsIMPsImpSiMPsimpSImpSiMpSimPsimPSImPsImpsIMpSimPsiMpSimPSimPSimPSimpSIMpsIMPSImpSIMPsImpsimPSImpsimPSimpSIMPsiMpsiMpsimpsIMpSImpsiMpSIMPSimpSiMPSiMPsIMpSiMpsiMpSimPSimpsimpSimpsImpSiMpsImpSImPsiMpsiMpSimpsiMPSIMpsIMpsimp/watch?v=tX8LuKtByTYsIMPSimPSImPSiMPSiMpSIMPsIMpsIMpsiMpsImPsimPsImPsimpsimpsImPsimpsIMPsiMpSiMPSimPsimPsIMpsiMpsIMpsiMPSIMpsIMpSImPsimPSIMpSimPSIMpsiMpSImpSiMPsimpsimpSImPsImpSimPsimpsIMPsImPsiMPSIMpsiMPSIMPSimpSIMPsiMPSimPSiMpsimPsimPSimpSImpsImPsimpSiMpsImPsImpsiMpsimpSimPsiMpSImpsimPsimPsimpsimpsImpsimpSimPsImPSiMpSIMpSiMpsIMpsIMpSiMpSimpsImPSiMpsimPSImPsImpSIMpsimpSImpSImpsIMpsImpSimPSIMPsimPsiMpSImPSIMPSIMpsIMPSimPsimPsimpsIMPsimPsImPsIMPSImPSIMpsiMPSIMPSIMpSImpsIMPSIMPSimPsImPSImpSiMpSImpsImPsiMpSimPSimpSiMpSiMpSIMPsiMpSiMpsImPsimPSimPsimpsiMpsIMpsimpsimpSImPSImpsImpSIMPsImPsiMpsImPsImpSimPsIMPsIMpSIMPSiMPsImpsimPSimpsImPsiMPSImPsiMPsiMpsImPsIMPsImPSiMPSIMpSIMpsImpSimpSImPsiMPSimpSImPsimPSimPsimpSiMpSiMPSImPsiMPsImPsImpSIMpsImPSimpsimPsImPSImPsiMpSImpSimpsimPsiMpSIMpSimpsiMPsimpsimpSimpSIMPsimPSIMPsiMPSIMpSIMpsImPsimPsiMpsiMPSiMPsiMPsiMpsImpSIMpSImPSIMpSIMpsImpSiMpsImPSiMPSImPSimpSiMpSIMpsImPsIMpSimpsIMPSiMpSIMPSiMpSIMPSimpsImPSImpsImPsImpsImpsiMpSiMPSimPSIMPSiMpsImPSImpsIMpSImPSimpSIMpsImpsimPSIMPsIMpsImpsIMpsiMpsimpSiMpsiMPsiMpsimpsImpsiMpsimPsimpSiMpSImPSIMpsimpsimpSiMPSiMpsiMPsiMPsiMPsiMpsiMPSImpsIMpsimpSimpSimpSIMpsiMpSIMpsIMPsIMPsimpSimpsimpSIMPSIMpSImpsimPsimPsimpSImpSiMpSimpSIMpSimPsiMpsiMPSImpSIMPsimPsimPSImPsIMPsImpsiMPSiMpSIMPSiMpsIMpsImpsimpSImpSiMPSIMpSIMpsImpsimPSiMpsIMpSImPSIMPSimpSImPSImpsimPsiMPsIMPsimPsImPSimpSIMpsimPsiMpsiMPsImPSimpsIMpsiMpsImpSimPSImPsImPSImpsiMpsImpsiMpsiMPSimPSIMpsimPsimPsImPsimPsIMpsimPSimpSimPsIMpSiMPsIMpsImpSImpsImPSIMPsimpSImPSImPsimPsiMpSiMPsiMPSimPSImPSimpsImPsImPsiMpsimPSiMpsImpsImPsimPsimPSimpsImPsimPsIMpSiMpSiMpSimPSiMPsImPsIMpSimpSiMPSiMpsIMpSiMpSimpsiMPsiMPSiMPsiMPSImpSImPsImPSimPSiMPSiMpsImPsiMpsIMPSiMp```
> Note: flag có dạng CyberFlag{______}

* :v Lúc đầu mình nhìn bài này cũng khá mệt, mình tưởng đây là một loại mã hóa gì đó và mình đã thử đi decode. Sau kha khá thời gian decode không thành công, mình xem lại đề kĩ hơn và phát hiện ```/watch?v=tX8LuKtByTY``` ở đâu đó trong đống SimP này. Đây là một đường link của ```Youtube```, nếu bạn để ý khi xem video trên Youtube cũng có đuôi tương tự.
* Sau đó mình dán đuôi này vào sau ```https://www.youtube.com/``` sẽ được video

```https://www.youtube.com/watch?v=tX8LuKtByTY```

![screenshoot](https://i.imgur.com/k8KnorU.png)

* Ở giây thứ 5 xuất hiện 1 đường link khác: ```https://ibb.co/X3Jz752```

![screenshoot](https://i.imgur.com/5Jspkr7.png)

* Haha tới đây mình tốn khá nhiều thời gian để tìm kiếm thông tin nhưng không có gì và quay lại link trước đó xem dưới phần mô tả thì mình nhận ra đã bị lừa :D Tuyệt vời 1 đường link khác: 

```https://pasteboard.co/Jv0czTk.jpg```

![screenshoot](https://i.imgur.com/qG1EErK.png)

* Tiếp tục 1 link youtube: ```/watch?v=oHg5SJYRHA0```


![screenshoot](https://i.imgur.com/K1UFIME.png)

![screenshoot](https://i.imgur.com/3lRlAtK.png)

* Ok tới đây thì hơi mệt vì bị lừa quá nhiều =)) lại thêm kha khá thời gian để tìm kiếm trên link này và quay lại link cũ tìm kiếm tiếp
* Vào Profile của người up video vào phân About mình phát hiện có dấu flag được mã hóa ```CyberFLAG{ZGF5IGtob25nIHBoYWkgbGEgZmxhZyBkYXU=}```

![screenshoot](https://i.imgur.com/R6mnFdG.png)

* Hahah nhưng không, rất may mắn là mình đã phát hiện ra cú lừa của tác giả khi nhìn xuống phần ```Link``` chỉ có dấu chấm là điểm bất thường, click vào thử xem

![screenshoot](https://i.imgur.com/e09jvcg.png) 

* Link dẫn tới phần video và mình tiếp tục tìm kiếm 
* Vào xem Profile của người đăng có Playlist là ```Cyber Space Jokes```, bị lừa khá nhiều và cái tên này đã làm mình chú ý.

![screenshoot](https://i.imgur.com/o8GMgpW.png)

* Lướt sơ Playlist thứ 14 và xem ở giây thứ 29 có đoạn mã hóa base64 bất thường: 

![screenshoot](https://i.imgur.com/oGon1xo.png)


* Các bạn có thể ngồi dùng notepad ngồi ghi lại đoạn mã đó, nhưng mình đã chụp màn hình lại và dán lên Yandex để lấy đoạn mã

```dGhhbmtzIGZvciB3YXRjaGluZyB0aGIzIGIzIHN0aWxsIGEgam9rZQ==```

![screenshoot](https://i.imgur.com/ojLXmnA.png)

* Decode xem =)) Ok muốn bỏ cuộc rồi ****. 
* Mò lại tiếp Playlist ```simp test``` còn lại
* Lướt sơ thì thấy một video với dòng chữ ```remember, don't be a simp pls```
* Hy vọng là không bị lừa nữa 

![screenshoot](https://i.imgur.com/DTaTf2R.png)

* Tới 2'13s bắt đầu xuất một loạt kí tự rất nhanh, mình đã phải tua chậm lại để lấy từng kí tự và nó cho ta một đường link: 

```spotify:/playlist/4MpF2Eh4ImzQTGS4vEIVrD```

* Mở link không được, sau khi tìm hiểu mình đã thêm ```open.spotify.com``` để mở được link

![screenshoot](https://i.imgur.com/Wxb6Yk9.png)

* Kiểm tra profile của ```Kiều Anh``` ta thấy ngay Flag



















 
 
 
 
 
 
 
 


 
 
 






