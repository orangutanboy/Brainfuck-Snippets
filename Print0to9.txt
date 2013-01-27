This prints numbers from 0 to 9

** Without comments **
++++++++++>>++++++[<++++++++>-]<-<[>+.<-]

** With comments **
set s0=10
++++++++++
set s1=47
>>++++++[<++++++++>-]<-
move to s0
<
while s0 != 0
[
	Add 1 to s1
	>+
	print s1
	.
	move to s0
	<
	decrement
	-
]
