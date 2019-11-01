# Emoji

According to this table from *"Wikipedia.org"* :

|Number of bytes|	First code point|	Last code point| Byte 1|	Byte 2|	Byte 3|	Byte 4|
|-------------|--------|----------|---|-------|------|-----|
|1|	U+0000 |U+007F  |	0xxxxxxx|   --------|   --------|   --------|			
|2| U+0080 |U+07FF  |	110xxxxx|	10xxxxxx|   --------|   --------|
|3| U+0800 |U+FFFF  |	1110xxxx|	10xxxxxx|	10xxxxxx|   --------|	
|4| U+10000|U+10FFFF|	11110xxx|	10xxxxxx|	10xxxxxx|	10xxxxxx|

emojies can be described in following codes:

| Emoji | Unicode | Binary | Number of bytes |
| ----------- | ----------- | ----------- | ----------- |
| ☺️ | U+263A | 11100010 10011000 10111010 | 3 byte |
| 😅    | U+1F605 | 11110000 10011111 10011000 10000101 | 4 byte |
| 👌    |  U+1F44C | 11110000 10011111 10010001 10001100 | 4 byte |
| 😳    |  U+1F633 | 11110000 10011111 10011000 10110011 | 4 byte |
| 😂    |  U+1F602 | 11110000 10011111 10011000 10000010 | 4 byte |

##References:
 - https://en.wikipedia.org/wiki/UTF-8
 - https://emojio.ru/smileys-people/d83dde05-1f605-nervnyy-smeh.html
 - https://emojio.ru/smileys-people/d83dde02-1f602-smeh-do-slez.html
 - https://emojio.ru/smileys-people/d83dde33-1f633-krasneyu.html
 - https://emojio.ru/skin-tones/d83ddc4cd83cdffb-1f44c-1f3fb-ok-horosho-svetlyy-ton.html
 - https://www.markdownguide.org/cheat-sheet/
 - https://habr.com/ru/post/138173/