# unitriangular_n5
data to find conjugation matrix given a orbit representative.

we give system of equations to solve on sagemath.
```
matrix {  {0,	  x_(1,2),  x_(1,3),	x_(1,4),	x_(1,5)},
          {0,	  0,        x_(2,3),	x_(2,4),	x_(2,5)},
          {0,	  0,        0,			  x_(3,4),	x_(3,5)},
          {0,	  0,        0,			  0,			  x_(4,5)},
          {0,	  0,        0,			  0,			  0}}
```

numbers in binary represent a matrix. 
	0 are entries with 0
	1 means non zero entries 
	order os entries are x_(3,5),	x_(2,4),	x_(2,5),	x_(1,3),	x_(1,4),	x_(1,5)
	ex.: #010111 means 
```
	{		{0,	0,			x_(1,3),	x_(1,4),	x_(1,5)},
			{0,	0,			0,			x_(2,4),	0},
			{0,	0,			0,			0,			0},
			{0,	0,			0,			0,			0},
			{0,	0,			0,			0,			0}}
```
