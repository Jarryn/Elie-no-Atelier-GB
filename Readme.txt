/* Information for

	Elie no Atelier GB (Japan) (SGB Enhanced)
	Gameboy Color

	Name: ATELIERELIEA8EJ
	Cart Type: MBC5
	MD5: 473e78b1d576a052492e1b4b80f4d3b3

	Provided by: Jazz
	@ the Romhacking.net community

/* TEXT Folder

	+ Edit: elie_commands.txt to put more addresses to dump in.
	+ Edit: Cartographer.bat to match rom name (default elie.gbc)

	+ File: elie_raw.tbl - used for hex editors
	+ File: elie_dump.tbl - used for Cartographer

/* KANJI Folder

	FILE		Table values (left to right)
	----		----------------------------
	F0-1.bmp	$F000 - $F03F
	F0-2.bmp	$F040 - $F07F
	F0-3.bmp	$F080 - $F0BF
	F0-4.bmp	$F0C0 - $F0FF

	F1-1.bmp	$F100 - $F13F
	F1-2.bmp	$F140 - $F17F
	F1-3.bmp	$F180 - $F1BF
	F1-4.bmp	$F1C0 - $F1FF (Completed to here)

	F2-1.bmp	$F200 - $F23F
	F2-2.bmp	$F240 - $F27F
	F2-3.bmp	$F280 - $F2BF
	F2-4.bmp	$F2C0 - $F2FF

	F3-1.bmp	$F300 - $F33F
	F3-2.bmp	$F340 - $F37F
	F3-3.bmp	$F380 - $F3BF
	F3-4.bmp	$F0C0 - $F3FF

	F4-1.bmp	$F400 - $F43F
	F4-2.bmp	$F440 - $F47F
	F4-3.bmp	$F480 - $F4BF
	F4-4.bmp	$F4C0 - $F4FF

Upload images to https://www.newocr.com/ for an automated tool at identifying the kanji. Quality check with KanjiTomo.

Note: See TEXT / table files for more details.

/* Starting Addresses

	Hex Addr	Description
	--------	-----------
	x90000		Introduction dialogue pointers (2 byte)
			($24) = Bank
			($01 $42) = x90201
			($3B $42) = x9023B...
	x90201		Introduction dialogue (Pointer = $01 $42)

	x1A4FF1		Menus / Objects / Names pointers (2 byte)
			($F1 $51) = x1A51F1
			($F9 $51) = x1A51F9...
	x1A51F1		Menus / Objects / Names (ATELIER)


	x100000		Kanji / Kata/Hira / Eng Graphic Tiles 1BPP

	x199041		Title Screen Graphics 2BPP
