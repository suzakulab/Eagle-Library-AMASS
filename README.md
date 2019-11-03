# Eagle-Library-AMASS
This AMASS connector Eagle library is an unofficial. If you notice a mistake, please contact the suzaku lab. info@suzakugiken.jp.

非公式のAMASS コネクター Eagleライブラリです。
お気づきの点がございましたら朱雀技研 info@suzakugiken.jp までお問い合わせください。

## AMASS connector Eagle Library
Now in Eagle 6 format.

### Installation (インストール方法)

1. Open Eagle and select the `Control Panel` window.
   Eagleを開きコントロールパネルを選択
2. Choose `Options` and from the drop down that appears, `Directories`.
   OptionからDirectoriesを選択
3. Change the Libraries line from: `$EAGLEDIR/lbr` to something like:
   Librariesの欄を次のように修正

    > $EAGLEDIR/lbr:$HOME/eagle_ext_lbrs (for macOS)

    > $EAGLEDIR\lbr;$HOME\eagle_ext_lbrs (for Windows)

4. Click `OK` to save your changes.
   OKで保存
5. Eagle will prompt to create the directory if it does not already exist.
   Note the location and choose `Yes` to create the directory.
   Yesをクリックしてディレクトリを作成

    > On macOS, `$HOME/eagle_ext_lbrs` changes to: /Users/suzaku/eagle_ext_lbrs/
    
    > On Windows, `$HOME\eagle_ext_lbrs` changes to: C:\Users\suzaku\Documents\eagle_ext_lbrs

6. Find and open the `eagle_ext_lbrs` folder. Unzip and drag `*.lbr` into the 
   new `eagle_ext_lbrs` folder.
   eagle_ext_lbrsを開いて、全てのlbrをコピーしてください。
7. Restart Eagle. The library should be now be usable. 
   Eagleを再起動


### Supported products

- amass.lbr
	- MR30
		- MR30PB-FB
		- MR30PB-M
		- MR30PW-FB
		- MR30PW-M
	- XT30
    	- XT30PW-F
		- XT30PW-M
		- XT30UPB-F
		- XT30UPB-M
	- XT60
		- XT60PB-F
		- XT60PB-M
		- XT60PT-F
		- XT60PT-M
		- XT60PW-F
		- XT60PW-M
	- XT90
		- XT90PB-F
		- XT90PB-M
		- XT90PW-F
		- XT90PW-M