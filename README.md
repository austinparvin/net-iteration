# .Net Iteration

A List of 10 koan accompanied by Assert tests to test the understanding of iteration/enumeration. 

## Includes:

- [C#](https://docs.microsoft.com/en-us/dotnet/csharp/)
- [LINQ](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/)
- compound LINQ statements

# Featured Code
## Compound LINQ Statement
```C#
public static IEnumerable<string> BestMovieOfTheYear(List<Movie> data, int year)
    {
      return data.Where(movie => (movie.Year == year && movie.Score > 90)).Select(movie => movie.Name);
    }
```
