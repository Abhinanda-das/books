---
title: "Nuggets from Vedic Mathematics"
original_title: "Vedic Mathematics - Nuggets"
tags:
  - "Английский"
cssclasses:
  - vedarama-book
source: Vedarama
source_url: "https://vedarama.com/en/books/vmn"
---

# Nuggets from Vedic Mathematics

## Introduction

The Vedas are ancient holy texts from India than can be legitimately characterized as the all-encompassing repository of (Hindu) knowledge from eons past. The term Vedic Mathematics refers to a set of sixteen mathematical formulae or *sutras* and their corollaries derived from the Vedas. The sixteen sutras are:

1\. Ekadhikena Purvena

2\. Nikhilam Navatashcaramam Dashatah

3\. Urdhva-tiryagbhyam

4\. Paraavartya Yojayet

5\. Shunyam Saamyasamuccaye

6\. (Anurupye) Shunyamanyat

7\. Sankalana-vyavakalanabhyam

8\. Puranapuranabhyam

9\. Chalana-Kalanabhyam

10\. Yaavadunam

11\. Vyashtisamanshtih

12\. Shesanyankena Charamena

13\. Sopaantyadvayamantyam

14\. Ekanynena Purvena

15\. Gunitasamuchyah

16\. Gunakasamuchyah

## Vedic Number Representation

Vedic knowledge is in the form of *slokas* or poems in Sanskrit verse. A number was encoded using consonant groups of the Sanskrit alphabet, and vowels were provided as additional latitude to the author in poetic composition. The coding key is given as **Kaadi nav, taadi nav, paadi panchak, yaadashtak ta ksha shunyam** Translated as below

\* letter "ka" and the following eight letters

\* letter "ta" and the following eight letters

\* letter "pa" and the following four letters

\* letter "ya" and the following seven letters, and

\* letter "ksha" for zero.

In other words,

\* ka, ta, pa, ya = 1

\* kha, tha, pha, ra = 2

\* ga, da, ba, la = 3

\* gha, dha, bha, va = 4

\* gna, na, ma, scha = 5

\* cha, ta, sha = 6

\* chha, tha, sa = 7

\* ja, da, ha = 8

\* jha, dha = 9

\* ksha = 0

For those of you who don't know or remember the *varnmala*, here it is:

ka kha ga gha gna

cha chha ja jha inya

Ta Tha Rda Dha Rna

ta tha da dha na

pa pha ba bha ma

ya ra la va scha

sha sa ha chjha tra gna

Thus *pa pa* is 11, *ma ra* is 52. Words *kapa*, *tapa* , *papa*, and *yapa* all mean the same that is 11. It was upto the author to choose one that fit the meaning of the verse well. An interesting example of this is a hymn below in the praise of God Krishna that gives the value of Pi to the 32 decimal places as .31415926535897932384626433832792.

Gopi bhaagya madhu vraata

Shrngisho dadhisandhiga

Khalajivita khaataava

Galahaataarasandhara

## 1. Ekadhikena Purvena

or *By one more than the previous one.*

The proposition "by" means the operations this sutra concerns are either multiplication or division. \[ In case of addition/subtraction proposition "to" or "from" is used.\] Thus this sutra is used for either multiplication or division. It turns out that it is applicable in both operations.

An interesting application of this sutra is in computing squares of numbers ending in five. Consider:

35x35 = (3x(3+1)) 25 = 12,25

The latter portion is multiplied by itself (5 by 5) and the previous portion is multiplied by one more than itself (3 by 4) resulting in the answer 1225.

It can also be applied in multiplications when the last digit is not 5 but the sum of the last digits is the base (10) and the previous parts are the same. Consider:

37X33 = (3x4),7x3 = 12,21

29x21 = (2x3),9x1 = 6,09 \[Antyayor dashake\]

We illustrate this sutra by its application to conversion of fractions into their equivalent decimal form. Consider fraction 1/19. Using this sutra this can be converted into a decimal form in a single step. This can be done either by applying the sutra for a multiplication operation or for a division operations, thus yielding two methods.

## Method 1: using multiplications

1/19, since 19 is not divisible by 2 or 5, the fractional result is a purely circulating decimal. (If the denominator contains only factors 2 and 5 is a purely non-circulating decimal, else it is a mixture of the two.)

So we start with the last digit

1

Multiply this by "one more", that is, 2 (this is the "key" digit from Ekadhikena)

21

Multiplying 2 by 2, followed by multiplying 4 by 2

421 =\> 8421

Now, multiplying 8 by 2, sixteen

68421

1 \<= carry

multiplying 6 by 2 is 12 plus 1 carry gives 13

368421

1 \<= carry

Continuing

7368421 =\> 47368421 =\> 947368421

1

Now we have 9 digits of the answer. There are a total of 18 digits (=denominator-numerator) in the answer computed by complementing the lower half:

052631578

947368421

Thus the result is **.052631578,947368421**

## Method 2: Using divisions

The earlier process can also be done using division instead of multiplication. We divide 1 by 2, answer is 0 with remainder 1

.0

Next 10 divided by 2 is five

.05

Next 5 divided by 2 is 2 with remainder 1

.052

next 12 (remainder,2) divided by 2 is 6

.0526

and so on.

As another example, consider 1/7, this same as 7/49 which as last digit of the denominator as 9. The previous digit is 4, by one more is 5. So we multiply (or divide) by 5, that is,

...7 =\> 57 =\> 857 =\> 2857 =\> 42857 =\> 142857 =\> .142,857 (stop after 7-1 digits)

3 2 4 1 2

## 2. Nikhilam Navatashcaramam Dashatah

or *All from nine and the last from ten.*

This sutra is often used in special cases of multiplication.

## Corollary 1: Yavdunam Jaavdunikritya Varga Cha Yojayet

or *Whatever the extent of its deficiency, lessen it still further to that very extent; and also set up the square of that deficiency.*

For instance: in computing the square of 9 we go through the following steps:

The nearest power of 10 to 9 is 10. Therefore, let us take 10 as our base.

Since 9 is 1 less than 10, decrease it still further to 8. This is the

left side of our answer.

On the right hand side put the square of the deficiency, that is 1^2.

Hence the answer is 81.

Similarly, 8^2 = 64, 7^2 = 49

For numbers above 10, instead of looking at the deficit we look at the surplus. For example:

11^2 = 12 1^2 = 121

12^2 = (12+2) 2^2 = 144

14^2 = (14+4) 4^2 = 18 16 = 196

and so on.

## 3. Urdhva-tiryagbhyam

or *Vertically and cross-wise.*

This sutra applies to all cases of multiplication and is very useful in division of one large number by another large number.

## 4. Paraavartya Yojayet

or *Transpose and apply.*

This sutra complements the *Nikhilam* sutra which is useful in divisions by large numbers. This sutra is useful in cases where the divisor consists of small digits. This sutra can be used to derive the Horner's process of Synthetic Division.

## 5. Shunyam Saamyasamuccaye

or *When the* ***samuccaya*** *is the same, that* ***samuccaya*** *is zero.*

This sutra is useful in solution of several special types of equations that can be solved visually. The word **samuccaya** has various meanings in different applicatins. For instance, it may mean a term which occurs as a common factor in all the termsconcerned. A simple example is equation "12x + 3x = 4x + 5x". Since "x" occurs as a common factor in all the terms, therefore, x=0 is a solution. Another meaning may be that **samuccaya** is a product of independent terms. For instance, in (x+7)(x+9) = (x+3)(x+21), the samuccaya is 7 x 9 = 3 x 21, therefore, x = 0 is a solution. Another meaning is the sum of the denominators of two fractions having the same numerical numerator, for example: 1/(2x-1) + 1/(3x-1) = 0 means 5x - 2 = 0.

Yet another meaning is "combination" or total. This is commonly used. For instance, if the sum of the numerators and the sum of denominators are the same then that sum is zero. Therefore,

2x + 9 2x + 7

------ = ------

2x + 7 2x + 9

therefore, 4x + 16 = 0 or x = -4

This meaning ("total") can also be applied in solving quadratic equations. The total meaning can not only imply sum but also subtraction. For instance when given N1/D1 = N2/D2, if N1+N2 = D1 + D2 (as shown earlier) then this sum is zero. Mental cross multiplication reveals that the resulting equation is quadratic (the coefficients of x^2 are different on the two sides). So, if N1 - D1 = N2 - D2 then that samuccaya is also zero. This yield the other root of a quadratic equation.

Yet interpretation of "total" is applied in multi-term RHS and LHS. For instance, consider

1 1 1 1

--- + ----- = ----- + ------

x-7 x-9 x-6 x-10

Here D1 + D2 = D3 + D4 = 2 x - 16. Thus x = 8.

There are several other cases where samuccaya can be applied with great versatility. For instance "apparently cubic" or "biquadratic" equations can be easily solved as shown below:

(x-3)^3 + (x-9)^3 = 2 (x-6)^3

Note that x -3 + x - 9 = 2 (x - 6). Therefore (x - 6) = 0 or x = 6.

consider

(x+3)^3 x+1

-------- = --------

(x+5)^3 x + 7

Observe: N1 + D1 = N2 + D2 = 2x + 8.

Therefore, x = -4.

This sutra has been extended further.

## 6. (Anurupye) Shunyamanyat

or *If one is in ratio, the other one is zero.*

This sutra is often used to solve simultaneous simple equations which may involve big numbers. But these equations in special cases can be visually solved because of a certain ratio between the coefficients. Consider the following example:

6x + 7y = 8

19x + 14y = 16

Here the ratio of coefficients of y is same as that of the constant terms.

Therefore, the "other" is zero, i.e., x = 0. Hence the solution of the

equations is x = 0 and y = 8/7.

This sutra is easily applicable to more general cases with any number of variables. For instance

ax + by + cz = a

bx + cy + az = b

cx + ay + bz = c

which yields x = 1, y = 0, z = 0.

A corollary (upsutra) of this sutra says **Sankalana-Vyavakalanaabhyam** or *By addition and by subtraction.* It is applicable in case of simultaneous linear equations where the x- and y-coefficients are interchanged. For instance:

45x - 23y = 113

23x - 45y = 91

By addition: 68x - 68 y = 204 =\> 68(x-y) = 204 =\> x - y = 3

By subtraction: 22x + 22y = 22 =\> 22(x+y) = 22 =\> x + y = 1

## 8. Puranapuranabhyam

or *By the completion or non-completion.*

## 14. Ekanynena Purvena

It is converse of the Ekaadhika sutra. It provides for multiplications wherein the multiplier digits consist entirely of nines.

------------------------------------------------------------------------

## "Rules of Thumb"

Many of the basic sutras have been applied to devise commonly used rules of thumb. For instance, the *Ekanyuna* sutra can be used to derive the following results:

\* Kevalaih Saptakam Gunyaat, or *in the case of seven the multiplicand should be 143*

\* Kalau Kshudasasaih, or *in the case of 13 the multiplicand should be 077*

\* Kamse Kshaamadaaha-khalairmalaih, or *in the case of 17 the multiplicand should be 05882353* (by the way, the literal meaning of this result is "In king Kamsa's reign famine, and unhygenic conditions prevailed." -- not immediately obvious what it had to do with Mathematics. These multiple meanings of these sutras were one of the reasons why some of the early translations of Vedas missed discourses on vedaangas.)

These are used to correctly identify first half of a recurring decimal number, and then applying Ekanyuna to arrive at the complete answer mechanically. Consider for example the following visual computations:

1/7 = 143x999/999999 = 142857/999999 = 0.142857

1/13 = 077x999/999999 = 076923/999999 = 0.076923

1/17 = 05882353x99999999/9999999999999999 = 0.05882352 94117647

Note that

7x142857 = 999999

13x076923 = 999999

17x05882352 94117647 = 9999999999999999

which says that if the last digit of the denominator is 7 or 3 then the last digit of the equivalent decimal fraction is 7 or 3 respectively.

## Some Interesting Nuggets and Examples:

\* **The Multiplication Sign "X" as a Cross-Addition:** Let us multiply (decimal numbers) 8 by 7: first column lists the numbers and the second column the deficits (from base = 10):

8 -2

X 7 -3

---------

The multiplication proceeds from the most signficant digit to least significant digit (which is natural since the positional numbers are also read from MSD to LSD, thus the result can be produced "on-line"). The first digit (most significant digit) is obtained by

1\. adding 8 and -3, or

2\. adding 7 and -2, or

that is,

8 -2

\\/

/\\

7 -3

This process of obtaining MSD of a multiplication by cross-addition is said to be the origin of the conventional cross sign for multiplication. BTW, you can generate the following digit by multiplication and (if necessary) by forwarding the carry to more significant digits. This method (derived from Nikhilam sutra) works multiplication of multidigit numbers and numbers greater than as well as less than the base (or half the base). Consider bit more complex examples below:

97 -3 102 2 888 -112

X 98 -2 X 104 4 X997 -003

----- ------ ---------

95,06 106,08 885,336

For cases when the numbers are closer to the middle of the base, Anurupyena sutra (according to the ratio) can be used to compute deficit/excess from a ratio of the base and then ratio the result:

48 -2 (base/2 = 50)

X46 -4

------

44,08 =\> 22,08

\* Division using "Seshaanyankaani charamena": to carry out a division first compute remainders and then multiply the remainders by the last digit and put down the last digit of the multiplicand. Consider: 1/7. When divising 1(0) by 7 the remainder is 3. Therefore, dividing 3 by 7 will subsequently lead to remainder 9 (= 3x3). But since 9 is more than 7 the remainder would be 2, so the remainder sequence is:

3, 2

Now 2 divided by 7 will have remainder of 6 (3x2), that is

3, 2, 6

Continuing

3, 2, 6, 4, 5, 1

We stop when the remainder sequence starts to repeat. Now, multiply these remainders by the last digit (7) of the denominator and keep only the first digit (LSD). So we have:

7x3 = 21 =\> put down 1

.1

3, 2, 6, 4, 5, 1

7x2 = 14 =\> put down 4

.1 4

3, 2, 6, 4, 5, 1

7x6 = 42 =\> put down 2

.1 4 2

3, 2, 6, 4, 5, 1

Continuing

.1 4 2 8 5 7

3, 2, 6, 4, 5, 1

So the answer is 1/7 = .142857142857...

## Acknowledgments

The illustrations are taken from the book **Vedic Mathematics** by Jagadguru Swami Shri Bharati Krishna Tirthaji Maharaja published by Motilal Banarasidass Publishers, Delhi, India.

------------------------------------------------------------------------

*rgupta@ics.uci.edu*

By David Osborn

I remember the time my father pulled me aside and said, "Son, you can explain everything with math." He was a rationalist, and for him God existed only in the sentiments of the uneducated. At the time I believed him, and I think his advice had a lot to do with my decision to pursue a degree in physics. Somewhere along the way, however, in 1969, something happened (something many people are still trying to figure out) which drew me away from the spirit of that fatherly advice and subsequently my once promising career.

Unfortunately, I think I went too far to the other side. I threw reason to the wind, so to speak, and unceremoniously became a self- ordained "spiritual person." Science, the foundation of which is mathematics, as I saw it, had nothing to offer. It was only years later, when the cloud of my sentimentalism was dissipated by the sun of my soul's integrity, that I was able to separate myself from yet another delusion—the first being the advice of my father, and the second being the idea that I could wish myself into a more profound understanding of the nature of reality.

Math cannot take the mystery out of life without doing away with life itself, for it is life's mystery, its unpredictability—the fact that it is dynamic, not static—that makes it alive and worth living. We may theoretically explain away God, but in so doing we only choose to delude ourselves; I = everything is just bad arithmetic.

However, before we can connect with our heart of hearts, our real spiritual essence, we cannot cast reason aside. With the help of the discriminating faculty we can know at least what transcendence is not. Withdrawing our heart from that is a good beginning for a spiritual life.

Mathematics has only recently risen to attempt to usurp the throne of Godhead. Ironically, it originally came into use in human society within the context of spiritual pursuit. Spiritually advanced cultures were not ignorant of the principles of mathematics, but they saw no necessity to explore those principles beyond that which was helpful in the advancement of God realization. Intoxicated by the gross power inherent in mathematical principles, later civilizations, succumbing to the all-inviting arms of illusion, employed these principles and further explored them in an attempt to conquer nature. The folly of this, as demonstrated in modern society today, points to the fact that "wisdom" is more than the exercise of intelligence. Modern man's worship of intelligence blinds him from the obvious: the superiority of love over reason.

A common belief among ancient cultures was that the laws of numbers have not only a practical meaning, but also a mystical or religious one. This belief was prevalent amongst the Pythagoreans. Prior to 500 B.C., Pythagoras, the great Greek pioneer in the teaching of mathematics, formed an exclusive club of young men to whom he imparted his superior mathematical knowledge. Each member was required to take an oath never to reveal this knowledge to an outsider. Pythagoras acquired many faithful disciples to whom he preached about the immortality of the soul and insisted on a life of renunciation. At the heart of the Pythagorean world view was a unity of religious principles and mathematical propositions.

In the third century B.C. another great Greek mathematician, Archimedes, contributed considerably to the field of mathematics. A quote attributed to Archimedes reads, "There are things which seem incredible to most men who have not studied mathematics." Yet according to Plutarch, Archimedes considered "mechanical work and every art concerned with the necessities of life an ignoble and inferior form of labor, and therefore exerted his best efforts only in seeking knowledge of those things in which the good and the beautiful were not mixed with the necessary." As did Plato, Archimedes scorned practical mathematics, although he became very expert at it.

The Greeks, however, encountered a major problem. The Greek alphabet, which had proved so useful in so many ways, proved to be a great hindrance in the art of calculating. Although Greek astronomers and astrologers used a sexagesimal place notation and a zero, the advantages of this usage were not fully appreciated and did not spread beyond their calculations. The Egyptians had no difficulty in representing large numbers, but the absence of any place value for their symbols so complicated their system that, for example, 23 symbols were needed to represent the number 986. Even the Romans, who succeeded the Greeks as masters of the Mediterranean world, and who are known as a nation of conquerors, could not conquer the art of calculating. This was a chore left to an abacus worked by a slave. No real progress in the art of calculating nor in science was made until help came from the East.

In the valley of the Indus River of India, the world's oldest civilization had developed its own system of mathematics. The Vedic *Shulba Sutras* (fifth to eighth century B.C.), meaning Ḍcodes of the rope,Ó show that the earliest geometrical and mathematical investigations among the Indians arose from certain requirements of their religious rituals. When the poetic vision of the Vedic seers was externalized in symbols, rituals requiring altars and precise measurement became manifest, providing a means to the attainment of the unmanifest world of consciousness. *"Shulba SutrasḌ* is the name given to those portions or supplements of the *Kalpasutras*, which deal with the measurement and construction of the different altars or arenas for religious rites. The word *shulba* refers to the ropes used to make these measurements.

Although Vedic mathematicians are known primarily for their computational genius in arithmetic and algebra, the basis and inspiration for the whole of Indian mathematics is geometry. Evidence of geometrical drawing instruments from as early as 2500 B.C. has been found in the Indus Valley.1 The beginnings of algebra can be traced to the constructional geometry of the Vedic priests, which are preserved in the *Shulba Sutras*. Exact measurements, orientations, and different geometrical shapes for the altars and arenas used for the religious functions (*yajnas*), which occupy an important part of the Vedic religious culture, are described in the *Shulba Sutras*. Many of these calculations employ the geometrical formula known as the Pythagorean theorem. This theorem (c. 540 B.C.), equating the square of the hypotenuse of a right angle triangle with the sum of the squares of the other two sides, was utilized in the earliest *Shulba Sutra* (the *Baudhayana)* prior to the eighth century B.C.Thus, widespread use of this famous mathematical theorem in India several centuries before its being popularized by Pythagoras has been documented. The exact wording of the theorem as presented in the *Sulba Sutras* is: ḌThe diagonal chord of the rectangle makes both the squares that the horizontal and vertical sides make separately."The proof of this fundamentally important theorem is well known from Euclid's time until the present for its excessively tedious and cumbersome nature; yet the Vedas present five different extremely simple proofs for this theorem. One historian, Needham, has stated, "Future research on the history of science and technology in Asia will in fact reveal that the achievements of these peoples contribute far more in all pre-Renaissance periods to the development of world science than has yet been realized."

The *Shulba Sutras* have preserved only that part of Vedic mathematics which was used for constructing the altars and for computing the calendar to regulate the performance of religious rituals. After the *Shulba Sutra* period, the main developments in Vedic mathematics arose from needs in the field of astronomy. The *Jyotisha*, science of the luminaries, utilizes all branches of mathematics.

The need to determine the right time for their religious rituals gave the first impetus for astronomical observations. With this desire in mind, the priests would spend night after night watching the advance of the moon through the circle of the *nakshatras* (lunar mansions), and day after day the alternate progress of the sun towards the north and the south. However, the priests were interested in mathematical rules only as far as they were of practical use. These truths were therefore expressed in the simplest and most practical manner. Elaborate proofs were not presented, nor were they desired.

A close investigation of the Vedic system of mathematics shows that it was much more advanced than the mathematical systems of the civilizations of the Nile or the Euphrates. The Vedic mathematicians had developed the decimal system of tens, hundreds, thousands, etc. where the remainder from one column of numbers is carried over to the next. The advantage of this system of nine number signs and a zero is that it allows for calculations to be easily made. Further, it has been said that the introduction of zero, or *sunya* as the Indians called it, in an operational sense as a definite part of a number system, marks one of the most important developments in the entire history of mathematics. The earliest preserved examples of the number system which is still in use today are found on several stone columns erected in India by King Ashoka in about 250 B.C.Similar inscriptions are found in caves near Poona (100 B.C.) and Nasik (200 A.D.).5 These earliest Indian numerals appear in a script called *brahmi*.

After 700 A.D. another notation, called by the name Indian numerals, which is said to have evolved from the *brahmi* numerals, assumed common usage, spreading to Arabia and from there around the world. When Arabic numerals (the name they had then become known by) came into common use throughout the Arabian empire, which extended from India to Spain, Europeans called them "Arabic notations," because they received them from the Arabians. However, the Arabians themselves called them "Indian figures" *(Al-Arqan-Al-Hindu)* and mathematics itself was called "the Indian art" *(hindisat)*.

Mastery of this new mathematics allowed the Muslim mathematicians of Baghdad to fully utilize the geometrical treatises of Euclid and Archimedes. Trigonometry flourished there along with astronomy and geography. Later in history, Carl Friedrich Gauss, the "prince of mathematics," was said to have lamented that Archimedes in the third century B.C. had failed to foresee the Indian system of numeration; how much more advanced science would have been.

Prior to these revolutionary discoveries, other world civilizations—the Egyptians, the Babylonians, the Romans, and the Chinese—all used independent symbols for each row of counting beads on the abacus, each requiring its own set of multiplication or addition tables. So cumbersome were these systems that mathematics was virtually at a standstill. The new number system from the Indus Valley led a revolution in mathematics by setting it free. By 500 A.D. mathematicians of India had solved problems that baffled the world's greatest scholars of all time. Aryabhatta, an astronomer mathematician who flourished at the beginning of the 6th century, introduced sines and versed sines—a great improvement over the clumsy half-cords of Ptolemy. A.L. Basham, foremost authority on ancient India, writes in *The Wonder That Was India*,"Medieval Indian mathematicians, such as Brahmagupta (seventh century), Mahavira (ninth century), and Bhaskara (twelfth century), made several discoveries which in Europe were not known until the Renaissance or later. They understood the import of positive and negative quantities, evolved sound systems of extracting square and cube roots, and could solve quadratic and certain types of indeterminate equations."Mahavira's most noteworthy contribution is his treatment of fractions for the first time and his rule for dividing one fraction by another, which did not appear in Europe until the 16th century.

B.B. Dutta writes: "The use of symbols—letters of the alphabet to denote unknowns, and equations are the foundations of the science of algebra. The Hindus were the first to make systematic use of the letters of the alphabet to denote unknowns. They were also the first to classify and make a detailed study of equations. Thus they may be said to have given birth to the modern science of algebra."The great Indian mathematician Bhaskaracharya (1150 A.D.) produced extensive treatises on both plane and spherical trigonometry and algebra, and his works contain remarkable solutions of problems which were not discovered in Europe until the seventeenth and eighteenth centuries. He preceded Newton by over 500 years in the discovery of the principles of differential calculus. A.L. Basham writes further, "The mathematical implications of zero (*sunya*) and infinity, never more than vaguely realized by classical authorities, were fully understood in medieval India. Earlier mathematicians had taught that X/0 = X, but Bhaskara proved the contrary. He also established mathematically what had been recognized in Indian theology at least a millenium earlier: that infinity, however divided, remains infinite, represented by the equation °/X = °." In the 14th century, Madhava, isolated in South India, developed a power series for the arctangent function, apparently without the use of calculus, allowing the calculation of ¹ to any number of decimal places (since arctan 1 = ¹/4). Whether he accomplished this by inventing a system as good as calculus or without the aid of calculus; either way it is astonishing.

By the fifteenth century A.D. use of the new mathematical concepts from India had spread all over Europe to Britain, France, Germany, and Italy, among others. A.L. Basham states also that "The debt of the Western world to India in this respect \[the field of mathematics\] cannot be overestimated. Most of the great discoveries and inventions of which Europe is so proud would have been impossible without a developed system of mathematics, and this in turn would have been impossible if Europe had been shackled by the unwieldy system of Roman numerals. The unknown man who devised the new system was, from the world's point of view, after the Buddha, the most important son of India. His achievement, though easily taken for granted, was the work of an analytical mind of the first order, and he deserves much more honor than he has so far received."

Unfortunately, Eurocentrism has effectively concealed from the common man the fact that we owe much in the way of mathematics to ancient India. Reflection on this may cause modern man to consider more seriously the spiritual preoccupation of ancient India. The *rishis* (seers) were not men lacking in practical knowledge of the world, dwelling only in the realm of imagination. They were well developed in secular knowledge, yet only insofar as they felt it was necessary within a world view in which consciousness was held as primary.

In ancient India, mathematics served as a bridge between understanding material reality and the spiritual conception. Vedic mathematics differs profoundly from Greek mathematics in that knowledge for its own sake (for its aesthetic satisfaction) did not appeal to the Indian mind. The mathematics of the Vedas lacks the cold, clear, geometric precision of the West; rather, it is cloaked in the poetic language which so distinguishes the East. Vedic mathematicians strongly felt that every discipline must have a purpose, and believed that the ultimate goal of life was to achieve self-realization and love of God and thereby be released from the cycle of birth and death. Those practices which furthered this end either directly or indirectly were practiced most rigorously. Outside of the religio-astronomical sphere, only the problems of day to day life (such as purchasing and bartering) interested the Indian mathematicians.

One of the foremost exponents of Vedic math, the late Bharati Krishna Tirtha Maharaja, author of*Vedic Mathematics*, has offered a glimpse into the sophistication of Vedic math. Drawing from the *Atharva-veda*, Tirtha Maharaja points to many *sutras* (codes) or aphorisms which appear to apply to every branch of mathematics: arithmetic, algebra, geometry (plane and solid), trigonometry (plane and spherical), conics (geometrical and analytical), astronomy, calculus (differential and integral), etc.

Utilizing the techniques derived from these *sutras*, calculations can be done with incredible ease and simplicity in one's head in a fraction of the time required by modern means. Calculations normally requiring as many as a hundred steps can be done by the Vedic method in one single simple step. For instance the conversion of the fraction 1/29 to its equivalent recurring decimal notation normally involves 28 steps. Utilizing the Vedic method it can be calculated in one simple step. (see insert for examples of how to utilize Vedic sutras)

In order to illustrate how secular and spiritual life were intertwined in Vedic India, Tirtha Maharaja has demonstrated that mathematical formulas and laws were often taught within the context of spiritual expression (*mantra*). Thus while learning spiritual lessons, one could also learn mathematical rules.

Tirtha Maharaja has pointed out that Vedic mathematicians prefer to use the *devanagari* letters of Sanskrit to represent the various numbers in their numerical notations rather than the numbers themselves, especially where large numbers are concerned. This made it much easier for the students of this math in their recording of the arguments and the appropriate conclusions.

Tirtha Maharaja states, ḌIn order to help the pupil to memorize the material studied and assimilated, they made it a general rule of practice to write even the most technical and abstruse textbooks in *sutras* or in verse (which is so much easier—even for the children—to memorize). And this is why we find not only theological, philosophical, medical, astronomical, and other such treatises, but even huge dictionaries in Sanskrit verse! So from this standpoint, they used verse, *sutras* and codes for lightening the burden and facilitating the work (by versifying scientific and even mathematical material in a readily assimilable form)!"8 The code used is as follows:

The Sanskrit consonants

*Ka, æa, pa,* and *ya* all denote 1;

*Kha, tha, pha,* and *ra* all represent 2;

*Ga, ṇa, ba,* and *la* all stand for 3;

*Gha, dha, bha,* and *va* all represent 4;

*Gna, ṭa, ma,* and *sa* all represent 5;

*Ca, ta,* and *êa* all stand for 6;

*Cha, æha,* and *Ẏa* all denote 7;

*Ja, da,* and *ha*all represent 8;

*Jha* and *ṇha* stand for 9; and

*KẎa* means zero.

Vowels make no difference and it is left to the author to select a particular consonant or vowel at each step. This great latitude allows one to bring about additional meanings of his own choice. For example *kapa, æapa, papa,* and *yapa* all mean 11. By a particular choice of consonants and vowels one can compose a poetic hymn with double or triple meanings. Here is an actual *sutra* of spiritual content, as well as secular mathematical significance.

*GOPI BHAGYA MADHUVRATA*  
*S¨ÁGI§O DADHI SANDHIGA*  
*KHALA J^VITA KHATŒVA*  
*GALA HŒLŒ RASANDHARA*

While this verse is a type of petition to Krishna, when learning it one can also learn the value of pi/10 (i.e. the ratio of the circumference of a circle to its diameter divided by 10) to 32 decimal places. It has a self-contained master-key for extending the evaluation to any number of decimal places.

The translation is as follows: "O Lord anointed with the yogurt of the milkmaids' worship (Krishna), O savior of the fallen, O master of Shiva, please protect me." At the same time, by application of the consonant code given above, this verse directly yields the decimal equivalent of pi divided by 10: pi/10 = 0.31415926535897932384626433832792. Thus, while offering mantric praise to Godhead in devotion, by this method one can also add to memory significant secular truths.

This is the real gist of the Vedic world view regarding the culture of knowledge: while culturing transcendental knowledge, one can also come to understand the intricacies of the phenomenal world. By the process of knowing the absolute truth, all relative truths also become known. In modern society today it is often contended that never the twain shall meet: science and religion are at odds. This erroneous conclusion is based on little understanding of either discipline. Science is the smaller circle within the larger circle of religion.

We should never lose sight of our spiritual goals. We should never succumb to the shortsightedness of attempting to exploit the inherent power in the principles of mathematics or any of the natural sciences for ungodly purposes. Our reasoning faculty is but a gracious gift of Godhead intended for divine purposes, and not those of our own design.

*David Osborn is an associate editor for* Clarion Call

1\. E.J.H. Mackay, *Further Excavations at Mohenjo-daro*, 1938, p. 222.

2\. Saraswati Amma, *Geometry in Ancient and Medieval India*, Motilal Banarsidas, 1979, p. 18.

3\. Dr. V. Raghavan, *Presidential Address*, Technical Sciences and Fine Arts Section, XXIst AIOC, New Delhi, 1961.

4\. Herbert Meschkowski, *Ways of Thought of Great Mathematicians,* Holden-Day Inc., San Francisco, 1964.

5\. Howard Eves, *An Introduction to the History of Mathematics*, Rinehart and Company Inc., New York, 1953, p. 19.

6\. A.L. Basham, *The Wonder That Was India*, Rupa & Co., Calcutta, 1967.

7\. B.B. Dutta, *History of Hindu Mathematics*, Preface.

8\. Jagadguru Swami Shri Bharati Krishna Tirthaji Maharaja, *Vedic Mathematics*, Motilal Banarsidass, Delhi, 1988.

Insert: **Vedic Mathematical Sutras**

Consider the following three *sutras:*

1\. ḌAll from 9 and the last from 10,Óand its corollary : ḌWhatever the extent of its deficiency, lessen it still further to that very extent; and also set up the square (of that deficiency).Ó

2\. "By one more than the previous one,*"* and its corollary: ḌProportionately.Ó

3\. "Vertically and crosswise," and its corollary*: "*The first by the first and the last by the last."

The first rather cryptic formula is best understood by way of a simple example: let us multiply 6 by 8.

1\. First, assign as the base for our calculations the power of 10 nearest to the numbers which are to be multiplied. For this example our base is 10.

2\. Write the two numbers to be multiplied on a paper one above the other, and to the right of each write the remainder when each number is subtracted from the base 10. The remainders are then connected to the original numbers with minus signs, signifying that they are less than the base 10.

6-4

8-2

3\. The answer to the multiplication is given in two parts. The first digit on the left is in multiples of 10 (i.e. the 4 of the answer 48). Although the answer can be arrived at by four different ways, only one is presented here. Subtract the sum of the two deficiencies (4 + 2 = 6) from the base (10) and obtain 10 - 6 = 4 for the left digit (which in multiples of the base 10 is 40).

6-4

8-2

4

4\. Now multiply the two remainder numbers 4 and 2 to obtain the product 8. This is the right hand portion of the answer which when added to the left hand portion 4 (multiples of 10) produces 48.

6-4

8-2

4/8

Another method employs cross subtraction. In the current example the 2 is subtracted from 6 (or 4 from 8) to obtain the first digit of the answer and the digits 2 and 4 are multiplied together to give the second digit of the answer. This process has been noted by historians as responsible for the general acceptance of the X mark as the sign of multiplication.

The algebraical explanation for the first process is

(x-a)(x-b) = x(x-a-b) + ab

where x is the base 10, a is the remainder 4 and b is the remainder 2 so that

6 = (x-a) = (10-4 )

8 = (x-b) = (10-2)

The equivalent process of multiplying 6 by 8 is then

x(x-a-b) + ab or

10(10-4-2)+2x4 = 40+8 = 48

These simple examples can be extended without limitation. Consider the following cases where 100 has been chosen as the base:

97 - 3 93 - 7 25 - 75

78 - 22 92 - 8 98 - 2

75/66 85/56 23/150=24/50

In the last example we carry the 100 of the 150 to the left and 23 (signifying 23 hundred) becomes 24 (hundred). Herein the *sutra'*s words Ḍall from 9 and the last from 10Ó are shown. The rule is that all the digits of the given original numbers are subtracted from 9, except for the last (the righthand-most one) which should be deducted from 10.

Consider the case when the multiplicand and the multiplier are just above a power of 10. In this case we must cross-add instead of cross-subtract. The algebraic formula for the process is: (x+a)(x+b) = x(x+a+b) + ab. Further, if one number is above and the other below a power of 10, we have a combination of subtraction and addition:

viz: 108 + 8 and 13 + 3

97 - 3  8 - 2

105/-24 =104/(100-24)=104/76 11/-6 =10/(10-6) = 10/4

The Sub-Sutra: ḌProportionatelyÓ provides for those cases where we wish to use as our base multiples of the normal base of powers of ten. That is, whenever neither the multiplicand nor the multiplier is sufficiently near a convenient power of 10, which could serve as our base we simply use a multiple of a power of ten as our working base, perform our calculations with this working base and then multiply or divide the result proportionately.

To multiply 48 by 32, for example, we use as our base 50 = 100/2, so we have

Base 50 48 - 2

32 - 18

2\\ 30/36 or (30/2)/36 = 15/36

Note that only the left decimals corresponding to the powers of ten digits (here 100) are to be effected by the proportional division of 2. These examples show how much easier it is to subtract a few numbers, (especially for more complex calculations) rather than memorize long mathematical tables and perform cumbersome calculations the long way.

## Squaring Numbers

The algebraic equivalent of the *sutra* for squaring a number is: (a+b)2 = a+ 2ab + b. To square 103 we would write it as (100 + 3)= 10,000 + 600 + 9 = 10,609. This calculation can easily be done mentally. Similarly, to divide 38,982 by 73 we can write the numerator as 38x+ 9x+ 8x + 2, where x is equal to 10, and the denominator is 7x + 3. It doesn't take much to figure out that the numerator can also be written as 35x+ 36x+ 37x + 12. Therefore,

38,982/73 = (35x+ 36x+ 37x + 12)/(7x + 3) = 5x+ 3x + 4 = 534

This is just the algebraic equivalent of the actual method used. The algebraic principle involved in the third *sutra*, "vertically and crosswise," can be expressed, in one of it's applications, as the multiplication of the two numbers represented by (ax+b) and (cx+d), with the answer acx+x(ad+bc)+bd. Differential calculus also is utilized in the Vedic *sutras* for breaking down a quadratic equation on sight into two simple equations of the first degree.Many additional sutras are given which provide simple mental one or two line methods for division, squaring of numbers, determining square and cube roots, compound additions and subtractions, integrations, differentiations, and integration by partial fractions, factorisation of quadratic equations, solution of simultaneous equations, and many more. For demonstrational purposes, we have only presented simple examples.

Formulas to be utilized within the suggested lotus graphic

ax+ bx = c:

x =Ã(4ac + b) - b \<-----this is the solution of the previous equation

2a

°/X = °

arctan 1 = ¹/4

(a+b)2 = a+ 2ab + b

pi/10 = 0.31415926535897932384626433832792

(ax+b)(cx+d) = acx+x(ad+bc)+bd

(35x+ 36x+ 37x + 12)/(7x + 3) = 5x+ 3x + 4

**Alwarnatha Prabhu please note: please check the alignment of all formulas and numerical notations** **in the final Pagemaker layout carefully with the original manuscript.** **In particular, the spacing may jump by one tab stop. Also,** **if the type size is changed it may affect the formulas which are** **not necessarily of the same size. ... keep an original copy with no changes.** **Also in many instances the use of italics for one word needs to be followed** **by two spaces before a roman word.**
