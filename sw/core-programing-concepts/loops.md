# VITANZI (LOOPS)

## Utangulizi

kitanzi ni mfuatano wa maagizo ambao hurudiwa mara kwa mara hadi hali fulani ifikiwe. 

**Tutaangalia aina mbili za vitanzi**
- kitanzi kwa (for)
- kitanzi wakati (while)

### kitanzi kwa (for)
*Kwa hutumika kurudia  kitu kinachoweza kurudiwa. Kitu kinachoweza kurudiwa ni mfuatano, safu au kamusi. Unatumia neno kuu la kwa likifuatiwa na kitambulisho kama vile k au v kikifuatiwa na kinachoweza kurudiwa. Kizuizi kinachoweza kurudiwa lazima kiwekwe kwenye mabano {}.*

 Hapa kuna mfano:

 Unda faili inayoitwa `kitanzi.nr` au `kitanzi.sw` na uandike kama hapa chini:

 ```go
 fanya neno = "Tanzania"

kwa i ktk neno {
	andika(i)
}
```

Hifadhi faili na uiendeshe kwenye terminal yako na:

```bash
nuru kitanzi.nr
```

Hivi ndivyo unapaswa kuona:

```go
T
a
n
z
a
n
i
a
```
**Key Value Pairs**

*Nuru hukuruhusu kupata thamani zote mbili au jozi ya ufunguo/thamani ya iterable. Ili kupata thamani pekee, tumia kitambulisho kimoja cha muda kama vile*

```go
fanya kamusi = {"a": "baba", "b": "mama"}

kwa v ktk kamusi {
	andika(v)
}
```
Hivi ndivyo unapaswa kuona:

```go
mama
baba
```

*Ili kupata ufunguo na thamani, tumia vitambulisho viwili vya muda:*

```go
fanya kamusi = {"a": "sufuria", "b": "mwiko"}

kwa k, v ktk kamusi {
	andika(k + " ni + " v)
}
```
Hivi ndivyo unapaswa kuona:

```go
a ni sufuria
b ni mwiko
```

**Vunja na Endelea**

*Kitanzi kinaweza kusitishwa kwa kutumia neno kuu **vunja***
mfano
```go
kwa i, v ktk "shule" {
        kama (i == 2) {
                andika("nimevunja")
                vunja
        }
        andika(v)
}
```
Hivi ndivyo unapaswa kuona

```go
s
h
u
nimevunja
```
*Kirudio mahususi kinaweza kurukwa kwa kutumia neno kuu la **endelea***
mfano:

```go
kwa i, v ktk "ugali" {
        kama (i == 2) {
                andika("nimeruka")
                endelea
        }
        andika(v)
}
```
Hivi ndivyo unapaswa kuona

```go
u
g
nimeruka
l
i
```
