# Puzzle

A toy project to help hone various skills, whilst also learning the new java 17 features.

## Objective

1. Create a sudoku generator, this creates the grid and fills in at least 17 squares in the puzzle.
2. Create a sudoku checker, where it will check if you have any incorrect squares
3. Create s sudoku solver, where it will solve any given solvable sudoku puzzle.

Also ensure that the code is extensible where it can be for other puzzles.
Bonus points for uses for switch statements, sealed classes and records.

## Acceptance Criteria  

Some basic acceptance criteria for creating the generator, in the form of unit tests

```java

@Test
@DisplayName("should an empty return grid")
public void shouldReturnAnEmptyGrid(){
        //given
        //when
        //then
        }

@Test
@DisplayName("Grid should be 9x9")
public void gridShouldBeNineByNine(){
        //given
        //when
        //then
        }

@Test
@DisplayName("Should return a populated grid, with 17 items populated")
public void shouldReturnAPopulatedGridWith17ItemsPopulated(){
        //given
        //when
        //then
        }

@Test
@DisplayName("no row should have a duplicate")
public void noRowShouldHaveADuplicate(){
        //given
        //when
        //then
        }

@Test
@DisplayName("no column should have a duplicate")
public void noColumnShouldHaveADuplicate(){
        //given
        //when
        //then
        }

@Test
@DisplayName("No square should have duplicates")
public void noSquareShouldHaveDuplicates(){
        //given
        //when
        //then
        }
```

---
### What's in the box  
In the project is a bare bones springboot project, a bit overkill but useful if you want to put a frontend onto it.
A gradle file with the minimum dependencies you will need and maybe some clues on some things to use.
