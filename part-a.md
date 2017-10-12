### A.  Normalizing data (40 points).

This question uses this table (from [the lecture notes](https://github.com/lse-st445/lectures/blob/master/week03/ST445_wk3_lecture.ipynb#normalization-example).  For each answer, please explain as fully as possible, and feel free to use tables or diagrams if you prefer.

1.  Why does this table violate the first normal form, and what would be required to make it 1NF?

2.  Why additional steps would be needed to make the table 2NF, and why?

3.  Why might we not want to normalize data to the fullest extent possible?

4.  In the table below, which of the three normalization rules does this violate, if any, and why?

    |  countryID  |  countryName    |   EUmember   |  EUjoindate  |
    | -----------:|:----------------|:------------:|:------------:|
    | 00001       | France          |  `true`      |  1958-01-01  |
    | 00004       | Hungary         |  `true`      |  2004-05-01  |
    | 00003       | Serbia          |  `false`     |       `NULL` |
    | 00004       | Finland         |  `true`      |  1995-01-01  |
    | 00005       | Russia          |  `false`     |       `NULL` |
    | 00006       | Ireland, UK     |  `true`      |  1973-01-01  |

    Are there any other problems with the table, besides normalization?

5.  What would it take to full (1NF-3NF) normalize this dataset?

    Write out these tables, and describe why this meets each of the normal forms.  This is a database of movies watched on NetBricks, a streaming movie service.

    | Name           | Address    |   Movies Rented   |  Salutation  | Category |
    |:---------------|:-----------|:------------------|:------------:|----------|
    | Bob Smith      | 1 Houghton Street    | _Star Wars_, _Inception_ |  Dr.   |  Scifi, Scifi |
    | Pry Ministair  | 10 Downing St     |  _Brexit the Movie_      |  Lady  | Tragedy |
    | Joe Bloggs     | 8 Myhatt St.      |  _Fast and Furious 6_, _Fast and Furious 7_     | Mr. | Action, Action |
