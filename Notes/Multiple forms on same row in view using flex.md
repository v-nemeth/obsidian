Tags: [[Developer]]
Time: 16-01-2025-10:48

#### *Abstract*
___


___

# Multiple forms on same row in view using flex


You can use bootstrap to reverse the flex column. Having a position absolute z-top places the form on top of the col-12. The first col in the col-12 class is important that this and the first col sums to 12 or less.

.row.flex-row-reverse
	.col-6.position-absolute.z-top
		=content_1
	.col-12
		=Potential form object
			.col-6
				=content_2
			.col-12
				=content_3



___
