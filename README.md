# TempStorage4Download

<div align="center">
<i>WAG - Wild Animal Gaming:</i><br>
<a href="https://www.twitch.tv/wildanimalgaming" target="_blank"><img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" alt="YouTube"></a>
<a href="https://www.youtube.com/channel/UCcjPG-iVUpkgPOyTyvMQ8zA" target="_blank"><img src="https://img.shields.io/badge/YouTube-%23E4405F.svg?&style=flat-square&logo=youtube&logoColor=white" alt="YouTube"></a>
<a href="https://www.facebook.com/groups/231599248862646" target="_blank"><img src="https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white" alt="Facebook"></a>
<a href="https://bit.ly/DiscordWildAnimalGaming" target="_blank"><img src="https://img.shields.io/badge/%3CServer%3E-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
<a href="https://steamcommunity.com/groups/WildAnimalGaming" target="_blank"><img src="https://img.shields.io/badge/steam-%23000000.svg?style=for-the-badge&logo=steam&logoColor=white" alt="Steam Group"></a>

</div>
---

## Minecraft

### Tải các phần mềm cần thiết

#### JavaSE
1.[JavaSE 8 trở lên][1]

#### Client Minecraft
2.[Minecraft Premium][2] <br>
3.[TLauncher][3] <br>
4.[BadLion][4] <br>
5.[Lunar][5] <br>
6.[LabyMod][6] <br> 
7.[TeckNix][7] <br>
8.[Salwvrr][8] <br>
9.[BatMod][9] <br>
10.[PvPLounge][10] <br>

#### Tải VPN LAN
11.[Radmin][11] <br>
12.[Hamachi][12] <br>

#### Tải các bộ thư viện hỗ trợ mod
13.[Minecraft Forge][13] <br>
14.[OptiFine][14] <br>
15.[OptiForge][15] <br>

#### Các link tải mods, shaderpacks và resourcepacks
16.[Creator Labs][16] <br>
17.[Curse Forge][17] <br>
18.[Shaders Mods][18] <br>
19.[Resource Pack][19] <br>
20.[9_Minecraft][20] <br>

#### Một số shaderpacks đẹp
21.[Complementary][21] <br>
22.[Astralex][22] <br>
23.[BSL][23] <br>
24.[Sildurs][24] <br>
25.[Kappa][25] <br>
26.[Continuum][26] <br>

#### Một số resourcepacks đẹp
27.[Creator Pack][27] <br>
28.[3D Sword][28] <br>
29.[3D Noteblock Display][29] <br>

#### Một số mods đẹp
30.[Mod Súng][30] <br>

### Cài đặt
``` sh
1. Cài đặt JavaSE từ các phiên bản 8 trở lên (>= 8)
2. Cài đặt Client Minecraft
3. Cài đặt VPN LAN
4. Tạo network hoặc tham gia network của VPN LAN
5. Cài đặt bộ thư viện hỗ trợ mods (Dành riêng cho Minecraft Premium):
    5.1 Quay lại nơi lưu các bộ thư viên hỗ trợ mod đã tải
    5.2 Lưu ý tải các bộ thư viện theo phiên bản của minecraft muốn chơi (vd: 1.18)
    5.3 Nhấp đúp hoặc chuột phải chọn Open with Java(TM) platform SE binary vào 2 file sau: 
        - Minecraft Forge
        - OptiFine
    5.4 Khởi chạy Minecraft Launcher
    5.5 Chọn trình chạy bằng OptiFine hoặc Forge
6. Tải các bộ shaderpacks, resourcepacks, mods theo sở thích (lưu ý không giải nén khi đã tải xong)
7. Tổ hợp phím Window + R
8. Gõ: %appdata%
9. Trỏ tới thư mục: .minecraft
10. Tạo thêm 2 thư mục có tên như sau: mods, shaderpacks
11. Copy từng file nén vào đúng folder (vd: các shader thì cho vào thư mục shaderpacks, các mod thì cho vào mods, các resource packs thì cho vào resourcepacks)
12. (Tuỳ mục đích) Di chuyển hoặc thay đổi thư mục gốc .minecraft từ %appdata% sang bất kì một ổ đĩa khác:
    12.1 Dành cho Minecraft Premium:
        - Copy thư mục .minercraft trong %appdata%
        - Chọn ổ đĩa, tạo thư mục và nhấp chuột phải chọn Paste để tiến hành copy
        - Mở Minecraft Launcher
        - Chọn tab Cấu hình (Installations)
        - Chọn vào 1 trong các trình chạy bên dưới
        - Tích vào dấu ba chấm để mở cài đặt Chỉnh sửa (edit)
        - Chọn vào Thư mục trò chơi (Game directory)
        - Trỏ vào thư mục .minecraft ở ổ đĩa mới
        - Nhấn Lưu (save)
    12.2 Dành cho các Client khác (Có thể dùng cách 12.1 trên nhưng không tạo host LAN, chỉ tham gia LAN):
        - Có thể dùng cách 12.1 bên trên nhưng sẽ không thể tạo host LAN được, chỉ có thể tham gia host của người khác.
        - Vào %appdata%, vào thư mục .minecraft
        - Unpin from taskbar icon client
        - Quay lại thư mục %appdata%
        - Nhấp chuột phải vào thư mục .minecraft chọn Cut
        - Chọn ổ đĩa, tạo thư mục và nhấp chuột phải chọn Paste để tiến hành di chuyển
        - Vào ổ đĩa mới, chọn icon Client và Pin to taskbar
        - Tổ hợp phím Window + R
        - Gõ: cmd
        - Gõ: mklink /J "%appdata%\.minecraft" "E:\MinecraftLauncher\.minecraft"
        - Sau khi hoàn thành thì 1 thư mục .minecraft được tạo ra trong thư mục %appdata% cũ. 
          Đó là đường link và dữ liệu game sẽ không lưu lại vào trong thư mục cũ nữa mà sẽ lưu ở ổ đĩa mới.
13. Cài skin
14. Tận hưởng game
```

### Tạo server
``` sh
Link: https://www.youtube.com/watch?v=wAraVu4ptqk
```

<!-- 
<p>1. 
    <a href="https://www.minecraft.net/en-us" target="_blank">Minecraft Premium</a>
</p> -->

[1]:https://www.oracle.com/java/technologies/downloads/archive/
[2]:https://www.minecraft.net/en-us
[3]:https://tlauncher.org/en/
[4]:https://client.badlion.net/
[5]:https://www.lunarclient.com/
[6]:https://www.labymod.net/en
[7]:https://tecknix.com/
[8]:https://www.salwyrr.com/
[9]:https://batmod.com/
[10]:https://pvplounge.com/
[11]:https://www.radmin-vpn.com/
[12]:https://www.vpn.net/
[13]:https://files.minecraftforge.net/net/minecraftforge/forge/
[14]:https://optifine.net/downloads
[15]:https://www.curseforge.com/minecraft/mc-mods/optiforge/files
[16]:https://creatorlabs.net/
[17]:https://www.curseforge.com/
[18]:https://shadersmods.com/
[19]:https://resourcepack.net/
[20]:https://www.9minecraft.net/
[21]:https://shadersmods.com/complementary-shaders/
[22]:https://shadersmods.com/astralex-shaders/
[23]:https://shadersmods.com/capttatsus-bsl-shaders-mod/
[24]:https://shadersmods.com/sildurs-shaders-mod/
[25]:https://www.curseforge.com/minecraft/customization/kappa-shader-by-rre36/files
[26]:https://continuum.graphics/continuum-shaders/
[27]:https://creatorlabs.net/downloads/creatorpack/
[28]:https://creatorlabs.net/downloads/3d-swords/
[29]:https://creatorlabs.net/downloads/3d-noteblock-displays/
[30]:https://www.9minecraft.net/modern-warfare-mod/?fbclid=IwAR2AubPlBcD7WJ7l0LhKaq6s7jy_VBTDgDJZfbo4sTziTKJidvlNoDCj-1w