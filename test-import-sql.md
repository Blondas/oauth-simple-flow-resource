```sql
INSERT INTO library (name, city) VALUES
    ('City Library', 'Zurich'),
    ('Central Library', 'Bern');

INSERT INTO book (title, author, library_id) VALUES
    ('Clean Code', 'Robert Martin', 1),
    ('The Pragmatic Programmer', 'David Thomas', 1),
    ('Refactoring', 'Martin Fowler', 1),
    ('Design Patterns', 'Gang of Four', 2),
    ('Domain-Driven Design', 'Eric Evans', 2),
    ('Spring in Action', 'Craig Walls', 2);

INSERT INTO review (content, rating, book_id) VALUES
    ('Excellent read, changed how I write code', 5, 1),
    ('Very practical advice', 4, 1),
    ('A must read for every developer', 5, 1),
    ('Timeless advice, still relevant today', 5, 2),
    ('Great examples throughout', 4, 2),
    ('Helped me think differently', 4, 2),
    ('Dense but worth it', 4, 3),
    ('Best book on refactoring', 5, 3),
    ('Clear and well structured', 5, 3),
    ('Classic, essential patterns explained', 5, 4),
    ('Hard to read but invaluable', 3, 4),
    ('Reference I keep coming back to', 4, 4),
    ('Deep and complex but rewarding', 4, 5),
    ('Changed how I model software', 5, 5),
    ('Not for beginners', 3, 5),
    ('Great intro to Spring', 4, 6),
    ('Well explained with good examples', 4, 6),
    ('Kept up to date with new versions', 5, 6);
```