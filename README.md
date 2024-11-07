매우 간단한 기능만 있는, utf-8 에디터가 필요해서, 공부겸 만들어 본겁니다.

git clone https://github.com/xixrio/rioedit.git
sudo dpkg -i rioedit.deb

Ubuntu에서 기본프로그램 등록
프로그램 등록하는 방법

.desktop
nano ~/.local/share/applications/rioedit.desktop

[Desktop Entry]
Version=1.0
Name=rioedit
Comment=A simple text editor built with Fyne
Exec=rioedit.exe %f
Icon=text-editor
Terminal=false
Type=Application
MimeType=text/plain;
Categories=Office;


입력하고 저장 
update-desktop-database ~/.local/share/applications

텍스트 파일 선택하고, 바로가기 지정함.
