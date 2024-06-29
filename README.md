# 
# PRINT STATEMENT:-
   1.Relation with print and variables:
     *using comma(,) we can add one data type inside the print with other data type and also comma will give one tab space.
     eg:-
       a=27
       print('my age is',a)
       output=my age is 27
      eg:-
        a=27
        b='usa'
        c=100.50
        print('i am at the   age of',a,'staying in',b,'and earning',c,'thousand dollars per year')

        #before going to 2nd technique first have a look into type conversion concept.

    2.using '+' we can add string data type along with given variable but make sure that the variables also string--> operator wont give one tab space.
    a=27
    print('my age is'+a)

    error:can only concatenate str (not 'int)

    a=27
    print('my age is'+str(a))

3.USING IDENTIFIERS:-
    %d-->int
    %f-->float
    %s--.str

    a=45

    print('my age is %d'%(a)  )

    a=27
    b='usa'
    c=20.55

    print('i am at the age of %d staying in %s earning %f thousand dollar per year'%(a,b,c))

 4.using { } and f--> functions:-
  a=27

  print(f'my age is { a}')

  a=45
  b='usa'
  c=20.55

  print(f'i am at the age of {a} staying in {b} and earning {c} thousand dollar per year')   








