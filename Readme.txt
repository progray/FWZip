FWZip ������ 1.0.11 �� 31 ������� 2015 ����.
�����: ��������� (Rouse_) ������
��������� ����: http://rouse.drkb.ru
��������� ����: http://alexander-bagel.blogspot.ru/
���������� ������ FWZip: http://rouse.drkb.ru/components.php#fwzip
����������� � ��������� ������� FWZip: https://github.com/AlexanderBagel/FWZip
mailto: rouse79@yandex.ru

0. � �������� ����������:

  � ��������� ����� �� ������ � ����� ����� ������������ � �������� ���������� ������ � ��������. 
  ������ ������ ��� ������� ����� ��� ������ ����� ���������������� - ZIP � � ����� ������ ��� ������������� ��������� ������ ��� ������ � �������� � ���� �������.
  ���������� ���������� ���� ������: ��� ���������� ��������� (����� �������) ������� �� ����� �� �� ����� ��������� ����������.
  ����� ����������� ������� ���������� �����. 
  �� ����� ������ ����� ���������� � �������������� ���������� � ����������� ����������.
  ����� �����-�� ����� ��� ����� ��� ��������� ������� �������� � ������������� ����� ������� ��������.
  ��� ����� �����-�� ����� ������������� ����� ��� ���� �� �� ������� ����� ��� ������ � ����������.  
  � ����� ������ ��� ������������� ��� �� �� ���� �������� � �������������� ��������,
  ���� �� ���� (�.�. �������� ���������� � �������� � XML - �.�. �������) ����� �� ����������� �������� ������ PPMD.
  � ����� � ���� ������� ���� �����-����� ���������� �������, �� ������� 400 �������� � �� ������� PPMD (sic).
  �������� ������ ��� ������ (������ PPMD ��� �� ��������, �� ����� - ����� �����)...
  
1. ����������� ����������:

  ����� ������� FWZip ������������ ��� �������� � ���������� ZIP ������� � �������� ������ Store � Deflate.
  
  � ������ ������ �������������� ��������� ����������� �������� ������������:
    - ��������� ZIP64 ����������
    - ��������� DataDescryptors
    - ��������� ������������ �� ������ PKWARE
    - ��������� ������������ ����� ������ � NTFS �����������
	- ��������� UTF8 ��������� � ������ ������
	
  �� �������������� �������� ������������ (���������� ����� �� ��� � �� ���� ��������� �� � ����� ����������):
    - �� �������������� ��������� ��������� ������ Shrunk, Reduced�, Imploded, TCA, Deflate64, PKWARE��, BZIP2
    - �� �������������� ������ ��������� ������������
    - �� �������������� ����������� ������
    - �� �������������� ���������� CentralDirectory
	
  ������� - ��� ��� ����� ������� WinRar ��� �������� ZIP ������, ������ ����� ������� �����.
  
  �������������� Delphi ������ �� ������� � �� XE8 ������������ (��� 32-����, ��� � 64).
  ������� ������ � ������� FireMonkey ���������� (iOS/Android ������ �� ��������������).
  
  �����!!!
  ��� ������������� ������ ���������� � ������� Delphi 2007 � ���� ����� ���� �������� � ����������� ������ � ����� � ���
  ��� � ����� �������� Delphi ������������ ���������� ������� ZLib. ��� ������ ���������� ��������.
  ������� ���������� � ������ 11.
  
  ��������� ������:
  FWZip �� ��������� ���������� �������� �������� ������� ������ ExData ��� ������ �� �������, ����������� ������ ������� ����� ������ MAXWORD.
  � ���������������� MAXWORD - ��� ������������ ����� ���� ExData ������ � ������. 
  � ����� � ���� � ��������� ������� ����� ��������� �������� ������ � ������� ExData � ������ �������� �� ����� ���� �� ��������� �� ������� �������� FWZip,
  ��� ��� ������ ����� ����� ��������� ���������� ������ ������ ����� ������� � ��� ����� ����� ������������� ��� ������ ��������.

2. ������ ���������:

  1.0 (�� 22 ������� 2011 ����): 
  
    - ��������� �����
	
  1.0.1 (�� 4 ����� 2011 ����):
  
    - ���������� ��������� �����. 
	  ������� ������� � ������ www.delphimaster.ru 
	  (������� �������, Riply, �. �����, clickmaker, �����, ������, Dennis I. Komarov, han_malign, brother, Sergey Masloff, antonn)
    - ������ �������� �� ������������ ���� � ������
	- ��������� �������� �� ����� ����
	- ������ ����������� ������ � ������ TFWZipReader. �.�. ����������� ���������� � ������� �������� �������� �� ��������, �� ������ �������� ������ � �� ����.
	- ��������� TFWZipWriterItem ���������� � ���� ������, ��� ��������� ������ ������� ReplaceItem
	- � ������� TFWZipReaderItem � TFWZipWriterItem ��������� �������� Tag
	- ���������� ������ ������� �� ���� � ����������� OnProgress ����������� ��� ������� ����� ���� �������� �������.
	- ��������� ������ � ������ ExData ������� �������� (��. ���� UseExDataBlob)
	
  1.0.2 (�� 4 ������ 2011 ����):
  
	- ���������� ������ ���������� ������ ����������� ��� ������ (Z_NO_COMPRESSION). 
	  �� ����������� ��������� erDone � ������ �������� ����������. 
	  ������� ������ ��������� ��� "Romkin", ������������� ������ ������.
	- ���������� �� ������ ���������� ��������� ���������� EZDecompressionError � ��������� ExtractToStream.
	- �������� �������������� ��������� erWrongCRC32 � ���� TExtractResult.
	  �� ������������ � ������ ���� �������� CheckCRC32 ������� ExtractToStream ��� �������� � False � ����������� ����� ������������ ����� �� ������� � ������������.
	- ���������� ���������� EZDecompressionError ������� �� EZLibError. 
	  ������� ���������� ������ ��� "@!!ex" �� ������ ������� �����.
	  
  1.0.3 (�� 29 ���� 2011 ����):
  
	- ��� ���, ��� ���������� ��������� � ����������� ������� ��������� ���������� ������������ ��� ������������ Delphi ������ 2009 � ����, ���������� zlib ������� � ��������� ����������. 
	  (��. �������� � ������ 9) ��� ������� � ����������� ������������� ��������������� �������� ZLib ��������� � ������ 10.
	- ���������� �������� ����������� ������� ���������� ����� �� ����� � ��������� ExtractAll (�� ���������� ������������� � UNC ����). ������� ����� ������ �� �������������� ������ ������.
	- ��������� ������� ����������� ��������� ����� � ������� ��� ���������� (���� � ��������� ������������� ���� FILE_ATTRIBUTE_READONLY, �� ����������� ���� ����� ���������� ������)
	- ��������� ������� OnDuplicate, ����������� ��� ������� ���������� ��� ������������� �� ����� �����
	- ����������� ����������� �� ������ ��� Fr0sT (��������� ������� �� ��������� ������ ����), � ������:
	- ���������� �������� � ������������ ��������� ������� � ���������� ����������.
	- �������� �������������� ���������� ����������� � ������ TFWZipWriter, ����������� ��������� ������ �� ���������.
	- ��������� �������������� ���������� ������� AddFolder � ������� ����������� ����������.
	- � ������� TZipProgressEvent ��������� ���������� Cancel ����������� ������������ �������� ������� ��������/���������� ������.
	- ��������� ��������� �������������� �������� ��� �������� ������ (��. ���� BuildWithException)

  1.0.4 (�� 21 ������� 2012 ����):
	- ��������� overload ��������� ExtractAll � ������ TFWZipReader. ������ ��������� ��������� �������������� �������� ExtractMask, 
	  ����������� �����, �� ������� ����� ����������� ����� ������ ��� ����������. (��. ���� ExctractZIPDemo1)
	- ��������� ��������� AddFilesAndFolders � ������ TFWZipWriter. (��. ���� CreateZIPDemo1)
	- ���������� ������ ��������� v1ctar, �� ��� ��� �������� �������.
	- ��������� ����� ���� ����������: EZipReader, EZipReaderItem, EZipWriter � EZipWriterItem.
	
  1.0.5 (�� 2 ������� 2012 ����)
	- ��������� ��������� ������� TFWZipReader.LoadFromFile � TFWZipReader.LoadFromStream. 
	  ��������� ��� ��������� ����������� ��������� ������� �� ������ � ����� ������ � ����� ��� ������ � �������. (�������� � ����� ���������� SFX ����).
	  
  1.0.6 (�� 14 ������� 2013 ����)
    - ��������� �������� TrimPackedStreamSize � ������ TFWZipWriter, ���������� ������ ����� � ����� ZLib ������. 
	  �� ��������� ������ �������� ��������.
	  ���� ������ �������� ���������, ��������� ����� �� ������ ������������� ��� ������ ���������� ICSharpCode.SharpZipLibrary, ����������� ���������� �������� �������.
	- ���������� ������������ ������ ���� VersionNeededToExtract.
	  ������� ������� ����������� ��� 'Grighome' �� �������������� ����������������� ������.
	- �������� ����� AddEmptyFolder ��� ���������� ������ �����.
	- ��������� �������� AlwaysAddEmptyFolder. ���� ��� ��������, ���������� ������ � ����� ���������� ������ ����� ����������� ���������� �� �� ���������.
	- ���������� ������ ��������� ������ ��������� END_OF_CENTRAL_DIR_SIGNATURE. 
	  � ������ ���� ��������� ��������� ������ ��� ������������� ZIP �����, �� ��� ������� ���� ��������� ����������� ������� ������ ���������.
	  ������� ��������� ������� �� �������������� ������ ������.
	  
  1.0.7 (�� 10 ���� 2013 ����)
    - ���������� ����������� ������ � ������ FWZipReader ���������� � ���������� ������ ���������� ��� �������� ����������� ������� �������������� ������.
	  ������� ����� ������� ��� 'Ega23' �� �������������� ������ ������.
	  
  1.0.8 (�� 14 ���� 2013 ����)
    - ��� ������������� �� ������������� � 64 ������ ������� ���������� ��� Delphi XE3.
	- ������� �������� ������ ��������� END_OF_CENTRAL_DIR_SIGNATURE, ����� ���������� �������.
	���������� ����� ����������� �� ���������� �����������:
	- ��������� ��������� ����� � ��������� UTF8. ��� ����� � ������ FWZipWriter �������� ���� UseUTF8String, ����-�� ���� �������� � ������ TFWZipWriterItem ��� ����� ������ ��������� ����������.
	  ����� FWZipReader ��������� ���������� ����� ������ � ���������������� �� � OEM ������ ��� �������� ������.
	- ��������� ��������� ZLibEx, ������ ������ ������� ������������ � ������� Delphi. 
	  ������������� ������ ���������� �������� ��������������� ��� ������� ����������. (��. �������� � ������ 11)
	- �������� ���� fwzip.inc � ������� ����� ��������� ������ ��������� ����������	  
	
  1.0.9 (�� 20 ���� 2013 ����)
    - �������� ����� ������������ � ������� ������������ (������� �������������� 6.3)  
    - ��������� �������� ������ �������� � protected ���� ��� ����������� ������� ������ (��. ���� ZipAnalizer)
    - �������� ����� ��������� ��������� TProgressState � ����������� ������� OnProgress
    ���������� ������ ������������ �������� �����������:
    - ��������� ��������� ������������ PKWARE ������ 6.3 � ����� ������ � �������� ����� 4 ��������. (� ��������� 7Zip ������� ������������ � ��������� Zip64EndOfCentralDir � ������� ������ ��������� SizeOfZip64EOFCentralDirectoryRecord ������������������ �� 12 ����, � ������� �� ������ ����������� WinRar/PkZip/WinZip)
    - ����� AddFolder ������ ���������� ���������� ���������� ����������� ������ � ������ ������ � ���������
	
  1.0.10 (�� 6 ������ 2013 ����)
    - � ����� TFWZipReaderItem ��������� �������� ItemIndex
	- �������� ����� ����� ���������� EZipReaderRead, ������������� ��� ������� ������ ������
	- �������� ����� ����� ���������� EZipWriterWrite, ������������� ��� ������� �������� ������
	- �� ���� ����������� ������ FWZipReader � �������� FWZipWriter ��������������� ����� ��������� ���������� �� ������.
	- �������� TrimPackedStreamSize �������� ���������� � �������� ������ ��� ���������� ��������� USE_AUTOGENERATED_ZLIB_HEADER
	���������� ����� ����������� �� ���������� �����������:	
	- ����� ����������� ������ ������� � ������ ��������
	- � ����� TFWZipReader ��������� ��������� �������� ������ Check (���������� �������� ���������� ��� ��������� ���������� ������)
	- ��� ����������� ������ � ��������� ������ �� ���� ������� ���� �� �� �������, ��������� ��� ��������� �������� psStart � psEnd ������������ ������� TFWZipReader (��. ��� TProgressState). 
	- �������� ������ ���������� �� ������������� deflateInit2_ (��. ���������� �����!!!)
	- ������ �������� � �������������� ����������
	���������� ������ ���������� �������� �������� ��������� � ��� ��� FWZip �� ��� ����������� ��������� ������ ��������� � 7Zip, � ������ ZLib �� ��� ����������� ����� ����� � �������������� ����������������� ��������� � ������� ������� inflateInit_. ���������� ������� ����������� � ���������� ����������������� ��������� � �������� �� ����� ������� inflateInit2_.
	- ���������� ���, ���������� � ������ ������ ����� ��� ��������� USE_AUTOGENERATED_ZLIB_HEADER, ������� ������� ���������� ����������� �� ������ � ����������� ������ ������.
	�����!!!
	������������� ������ ����������� ��� ����������� ������ ZLib �������� ������ ������� � Delphi 2009 � ����. ��� ����� ������ ������ Delphi ������������� ����� �������� ��������� USE_AUTOGENERATED_ZLIB_HEADER, ����������� �� ������ ������� ������/����������. ���� ��������� ������� ������ ����������� ���������� � FWZip ���������� ���������� ZLibEx (���� �������� ��������� USE_ZLIB_EX), ���� ��������������� ����������� ����� ���������� ����������� ��������� USE_ZLIB_DLL.

  1.0.11 (�� 31 ������� 2015 ����)
	- �������� ����� TFWZipModifier, ����������� ����������� ����� ��������� ������ "�� ����" � �� ��������� ����������� ������.
    - ��������� ��������� � ������ FWZipReader, ������� ������� ������ �����, ��-�� ����������� �������������� END_OF_CENTRAL_DIR_SIGNATURE	
	- ���������� ��������� ������ ��� �������� ������ � ������ ���� ���������� ������� ���� (������� �������������� ��������)
	- ��������� �������� ����� �������� TFileStream � ��������� TFWZipReader.LoadFromFile  
    ����������� ����������� �� ������� �������:
    - � ������ TFWZipReader ��������� �������� DefaultDuplicateAction, ����������� ��������� �������� �� ��������� ��� ����������� ���������� ��������������� ������.  
	���������� ������ ������������ �������� �������� � ����������� ����� �����������:
	- ���������� ������ ����� � ���������� ���������� MAXDWORD ��� ������� �� ������ ��������� ����������� ������� � ������������� ZIP64
	- � LocalDirectory ������ ������� ���������� � ZIP64 (��� ��������� ���������� ������-�� �� ����� �� ������ �� CentralDirectory)
	- �������� ���������� ����� Extract � ������ TFWZipReaderItem ����������� �������� ��� ���������������� �����
    ���������� ������ ��������� �������� ��������:
	- ��� ������������� UTF8 ���������� RangeCheckError � ��������� TFWZipReaderItem.InitFromStream ��� �������� ����� ����� �� �������������� ����������.
	
3. �������� ������:

  - .\FWZipConsts.pas - ���� � ��������� ������������ ��� ������ � ZIP ��������
  - .\FWZipCrc32.pas - ����� ������� ��� �������� ����������� ����� ����� ������
  - .\FWZipCrypt.pas - ���������� ������������ �� ������ PKWARE
  - .\FWZipModifier.pas - ����� ��� ����������� ����� ��������� ZIP ������� ��� ����������� ������������ ������.
  - .\FWZipReader.pas - ����� ������� ��� ���������� ZIP ������  
  - .\FWZipStream.pas - ��������������� ����� ��� ��������� ���������� �� ���� � ���������� ��������� ZLib
  - .\FWZipWriter.pas - ����� ��� �������� ZIP ������
  - .\FWZipZLib.pas - ������� ������ ������ � ����������. �������� �� ZLibEx � ��������� ������ ��� ������������� �� ������� �������� Delphi
  - .\fwzip.inc - ��������� ����������� ��������� �������� ���������� 
  
  - .\Demos\ - ����� � ����������������� ���������
  - .\Demos\FWZipDemos.bpg - ProjectGroup �� ����� ������������� ��� Delphi7
  - .\Demos\FWZipDemos.groupproj - ProjectGroup �� ����� ������������� ��� Delphi 2007 � ����
  - .\Demos\Create ZIP 1\CreateZIPDemo1.dpr - ������������ �������� ������ ��������� ��������� �������� ���������� ������
  - .\Demos\Create ZIP 2\CreateZIPDemo2.dpr - ������������ �������� ������ � ��������� ����������� �������
  - .\Demos\Extract ZIP 1\ExctractZIPDemo1.dpr - ������������ ���������� ������.
  - .\Demos\Extract ZIP 2\ExctractZIPDemo2.dpr - ������������ ���������� �������������� ������.
  - .\Modify ZIP\ - ����� � ��������� ����������� ������� ��� �� �����������
  - .\Modify ZIP\Merge two ZIP\MergeZip.dpr - ������ ����������� ������ �� ���������� ������� � ����
  - .\Modify ZIP\Replace data in ZIP\ReplaceZipItemData.dpr - ������ ��������� ����� ������ � ������ �� ��������� ����������� ������������ ������.
  - .\Modify ZIP\Split ZIP\SplitZip.dpr - ������ �������� ������ �� ��������� ������.
  - .\Demos\Use ZIP ExData\UseExDataBlob.dpr - ������������ ������ � ������ ExData ������� �������� ������.
  - .\Demos\Test Build With Exception\BuildWithException.dpr - ������������ ��������� �������������� �������� ��� �������� ������.
  - .\Demos\PerfomanceTest\ - ����� � �������� ������������ ������������������.
  - .\Demos\DemoResults\ - ����� ��������� ��� ������ ���������������� ��������.
  - .\Demos\ZipAnalizer\ - ����� � �������� ����������� ZIP ������� � �������������� FWZipReader
  - .\Demos\ZipAnalizer2\ - ����� � �������� ����������� ZIP ������� � �������������� ������������ ��������
  
  - .\Doc\* - ������������, �� ��������� ������� ������ ���������� ������� ������ �������.    
  
  - .\zlib_external.pas - ���� ��� ����������� ������� ���������� (��. �������� � ������ 9) - �������
  - .\zlib_dll\ - ����� � �������� ������� ����������
  - .\zlib_dll\zlib_d2010.dpr - ������ ������� ����������
  - .\zlib_dll\zlib_d2010.dll - ���������������� ����������  
  
4. �������� ������:

��� �������� ������ ����������� ����� TFWZipWriter.
������� ��������:
  - ������� TFWZipWriter
  - ��� ������ ������� AddStream/AddFiles/AddFolder ������� ���������� ��������� ������.
  - ��������� ������ ��������� ������� �������� ��� ������ ��������� ������� ������ TFWZipWriterItem
  - ��� ������������� ������� ������ �������� ������� ������ DeleteItem ��� Clear
  - ���������� ���������� � ������
  - �� ������������� ��������� ����������� OnException, OnProgress � OnSaveExData
  - ������� ����� BuildZip	
  - ���������������� ��������� ������ ������ BuildZip
  - ��������� TFWZipWriter
  
4.1 - ����������� ������

��� ����������� ������ ����������� ����� TFWZipModifier, ���������� ������������ TFWZipWriter.
������� �������� ���������� �������� ������, �� ����������� ������� ���� �������������� �������:
  - AddZipFile - ��������� ��� ������������ ����� �� �������� ����� ������� ������ �� ��������� �����������
  - AddFromZip - ��������� ������ �� ������������� ������ � ������� (������� ������ AddStream)

�������� ������� � ����� .\Demos\Modify ZIP\
  
5. ���������� ������:

��� ���������� ������ ����������� ����� TFWZipReader
������� ��������:
  - ������� TFWZipReader
  - ������� ����� ������� ������� LoadFromFile/LoadFromStream
  - ��� ������� ��������� �������� ����������� ������ ������� ������ Check
  - �� ������������� ��������� ���������� OnProgress
  - �������������� ���������� ����� ������:
	- ���� ����� ����������, �� �������� ������ ������� �������� PasswordList ��� ��������� ���������� OnPassword
	- ���� �������������� ������ � ������ ExData ��������� ���������� OnLoadExData
	- �� ������������� ��������� ���������� OnExeption. � ��� �� ������ ��������� �������, ���������� ���������� ������ ��� ���������� ��� ��������.
	- ������� ����� ExtractAll
  - ������ ���������� �����������:
    - ������� ����������� ������� ������ ��� ������ TFWZipReader.Item[Index] � ������� ����� Extract/ExtractToStream
	- ���� �������������� ������ � ������ ExData ��������� ���������� OnLoadExData ���������� ��������
	- ���� Extract/ExtractToStream ������ erNeedPassword, ��������� ����� ������ ��� ���� ������ ������ ������
  - ��������� TFWZipReader
  
6. ����������� ���������� �������:

� ��������� �������� ����������� �������� ��������� ����������� �������, � NTFS ������� (ExDataTag = $0E, � �������� �� � ���� ������ �� ������� ������� � ������������� ����� ExData ����������� ������).
���-�� ����������� ��������� X.509 ������������ � ��������� ������� ������ (BZIP2, LZMA, PPMD). 
��, �.�. ������ ����� ������� ������� ��� ����, �� ������ ���������� ����� ��������� ������ �� ���� �� ������������� � ���� �������� ������.

7. ������������������:

  - ����� ��������� ������ ������������� ������ ��� CentralDirectory = SizeOf(TCentralDirectoryFileHeaderEx) * ���������� ��������� ������.
  - ������� ����� ������������ ������ ��� ������ 400��, � ����� �� �������������.
  - ������� ����� ������������ ������ ��� ���������� 100��, � ����� �� 160��.
  ������������ ������������� �� �������� ������ ����� � ����� �������� � �����, � ���������� �������� �� ������ � ���� �� �����. 
  ��� ������������� ������������� ������� - ������ ������ ����������� ����������.
  
  ���������� ����������� ������ (������� ������ clDefault):
  
  - ��������� 3 ����� �� 3 6 � 9 ��������:
	(������������� ������������� ZIP64 ���������� ��-�� ���������� �� ������� ���������)
    - ������ CentralDirectory: 378 ����
    - ���������� ���������: 3
	- ����� ����� ������: 18,989,302,272 ���� (~17 ��������)
    - ����� ������: 30 �����
	- ������� ������ ������ ��� ������: 396,085 ����
	- ������� ������ ������ ��� ������: 396,099 ����
	- ����� ����������: 15 �����
	- ������� ������ ������ ��� ����������: 170,413 ����
	- ������� ������ ������ ��� ����������: 170,420 ����

  - ��������� ����� Program Files �� ������� ����� � ������������� Windows XP, ��� �������� ����������� ������� "qwe":
	(������������� ������������� ZIP64 ���������� ��-�� ���������� �� ���-�� ��������� + ������������� ������������)	
    - ������ CentralDirectory: 11,264,400 ���� (~10 ��������)
    - ���������� ���������: 89,400 
	- ����� ����� ������: 43,748,481,918 ���� (~40 ��������)
    - ����� ������: 1 ��� 56 �����
	- ������� ������ ������ ��� ������: 403,953 ����
	- ������� ������ ������ ��� ������: 413,636 ����
	- ����� ����������: 40 �����
	- ������� ������ ������ ��� ����������: 158,419 ����
	- ������� ������ ������ ��� ����������:	172,628 ����

8. ����������� ������:

��� ������������ ������ ���� ExData (�� ����������� ZIP64) �� ������� � LocalDirectory (�� ������������ ��� ������� ��� �� �����������, ���� �� � ����� ��� ��������������). 
�.�. ����-�� ���� ������������ � CentralDirectory, �� � �������� �� ����������� ����������� ������ ������ �������� �������� ����������.

��� ���������� ������ � ������ ���������� �������� DataDescryptors ��� ������� �������������� �������� (��������� ������� ����� �� ��������� ����������� � ������������ ������ TFWZipWriter).
���� � ���, ��� ��� ���������� ���������� ������������� ��������� ������������� �����, � �������� �������� ��������� ����������� ����� ����� ��� (��� ���������� DataDescryptors) ����� ����������� �����.
���� �� ������� DataDescryptors �� �������� ���������� ���� ��� ����. ������ ��� ����� ���������� ��������������� ��� ��������� CRC32, ������ ��� ��� ��������������� ��� �������� �����. ����� ������� ����� ������������ �������������� ������ � ������������ DataDescryptors � ��� ���� ������ ��� � �����������. ����-�� ����������� ����� ������������ � ����� ������ �� ���� ��� ������ ������.

���� ���������� �� ������������, �� DataDescryptors ���������� ���������, � ����� �������� 20 ���� �� ������ ������� ������.

���������� ������� ����� � ����� ������� ������� �� ����������.
�� ������� ��� ������ ������� Deflate, ����������� ZLib-�� ����� �������� ZLibHeader �������� � ��� �����.
� �� ���� ������� �������������� � ������ ��������� �������, ������� ����� ���� ������ ����� �� ��� ������� ����� 2 �����, � ����� ����� ������ ��� ����� (�� ��� EncryptedFileHeader) ������� ��� ��� �����.
��������� ����� ������� ��������� TFWZipItemStream, �� ��� �����, ������ ������ :) 
��� ����� - ����� �������.

9. ������������� ������� ���������� (��������, ��. ����� 11)

��� ������������� FWZip � ������� Delphi ���� 2010 ��������� ����� ��� "@!!ex" ��������� ������.
��������� ������, ��������� ���������� ������������, �� ��������������. ������� ��� ���� ���, ��� ������ ������ Delphi ���������� ���������� ��� ZLib, ������� �� �������� ���������� ���������� ���������� ������� ������. ��� ������ ��� Delphi 2010 � ����, ������ ������ ��������.
�.�. ��� ZLib ��������� � zlib.dcu, � ���� DCU ������ ������ �� ���������� ����� �����, �� �������� �������� ��������� ����������, ������������� ��������� ������� � ��� ����, � ������� ��� ����������� � 2010-�� ������:

	- deflateInit_
	- DeflateInit2_
	- deflate
	- deflateEnd
	- inflateInit_
	- inflateInit2_
	- inflate
	- inflateEnd
	- inflateReset
	- adler32

��� ������������� ������ ����������, ���������� �������� ���������� ��������� USE_ZLIB_DLL � �����, ������ ������������ ����� ZLib, ������������� � Delphi, FWZip ����� ������������ ���� ZLib_external, ������� ����� ����������� ����� ������ ������� �� �� zlib.dcu, � �� ����������.

10. ������������� ZLib ������������ � Indy (��������, ��. ����� 11)

��� ���� ������� ������ ���������� ZLib ��������� ����� �����. 
1. ���������� ������� � ���������� ����� ��������� ������ Indy �� ��������� ������: ftp://indy.fulgan.com/ZIP/ 
�� ����� ������� 2012-�� ���� ������ ������ ���� ���������: ftp://indy.fulgan.com/ZIP/Indy10_4736.zip
2. ��������� ���� � ����� � ZLib (.\Lib\Protocols\ZLib\)
3. ������� ���� ���� ����� ������ � ���������� ������� (��� � ���������� IDE, ������ ��� �� ��� ����������)

11. ������������� ZLibEx (��������������� �������)

�������� ���������� ������� ������� ������� � �������� ���������� �������, ��������� � �������������� ����� ����� ������ ZLib ��������� ��������� �����������.
1. ���������� ������� � ���������� ����� ��������� ������ ZLibEx �� ��������� ������: http://www.base2ti.com/
2. ��������� ��������� � ������������ � �������������� � ������� "installation" �� ����� Readme.txt
3. �������� � ���������� ������� ���������� ��������� USE_ZLIB_EX