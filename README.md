# Benchmarking ActiveRecord Yelp Exercises

## Learning Goals

- Use benchmarking to measure and improve performance in ruby

## Instructions

Go back to your solution to the [ActiveRecord Yelp Exercises](https://github.com/learn-co-curriculum/activerecord-yelp-exercises)

- Add benchmarks to your methods to find the slowest queries
- Rewrite the slowest 3 methods. Keep the slow implementations around, so that
  your benchmarks can output comparisons of the fast and slow versions.
- Update your seed file to add a few tens of thousands of rows to your tables.
  Rerun your benchmarks to compare versions of your code, and see what's
  different.
- Repeat for a few hundreds of thousands of rows. A few million.
- Ask a colleague to review your benchmark code and results

> Hint: If you are doing operations in ruby, how could you move those operations
> to the database? Are you missing any indexes? Do you have any N+1 queries?
>
> Note: If everything seems too fast to notice differences, benchmark and
> compare the versions before and after the adding indexes and fixing n+1
> queries.
