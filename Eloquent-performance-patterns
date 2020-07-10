# Eloquent Performance Patterns

### Faster ordering using compound indexes
- Pagination without order by is really bad idea and sometimes we do not able to see some records simply because order of those records changes whilte navigating from one page to another. whenever we use pagination be sure to include order by statement
- Order by multiple columns is not efficient on database, which introduce concept of compound index
- when we use compound index on order by statement, the order of the column in that compound index matters
### Filtering and sorting dates
- use of rawIndex which could also useful in where condition
