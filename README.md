comic_release.rb
================
�R�~�b�N�V���̔������𒲂ׂ�Ruby�X�N���v�g�ł��B
���݂́A[comiclist.jp](http://comiclist.jp/)����A�����擾���Ă��܂��B

�g�p���@
--------
	> ruby comic_release.rb list.csv

�ϐ��ꗗ
--------
+ Comic
	+ `title` : �^�C�g��
	+ `volume` : ����
	+ `is_release_decided` : �����t���O
+ ComicList
	+ `url` : �����pURL
	+ `release_daye` : ������

���\�b�h�ꗗ
============
+ ComicList
	+ `create_encode_url` : title��volume����AUTF-8�G���R�[�h�Ō����p��URL�𐶐��B
	+ `get_release_date` : URL����HTML���擾���A���K�\����p���Ĕ��������擾�B

�N���X�}
--------
![class.png](https://raw.github.com/hico-horiuchi/comic_release.rb/master/class.png)

�V�[�P���X�}
------------
![sequence.png](https://raw.github.com/hico-horiuchi/comic_release.rb/master/sequence.png)
