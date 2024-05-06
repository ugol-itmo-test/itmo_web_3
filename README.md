# itmo_web_3

### Part 3 (select's)
- table messages
<img width="966" alt="image" src="https://github.com/ugol-itmo-test/itmo_web_3/assets/103264273/0934b6a1-45a0-446d-a95b-36037cf2447b">

- table users
<img width="985" alt="image" src="https://github.com/ugol-itmo-test/itmo_web_3/assets/103264273/f683be38-95c5-46d3-b0be-93c6c1396f79">


1. select username from users
<img width="130" alt="image" src="https://github.com/ugol-itmo-test/itmo_web_3/assets/103264273/f685bc80-cca9-406b-8b4b-74dbb335e8ed">

2. select u.username, count(m.id) from users as u, messages as m where u.id = m.from group by u.username
<img width="222" alt="image" src="https://github.com/ugol-itmo-test/itmo_web_3/assets/103264273/1e5763cf-023c-4b7f-96da-f6fdef5fce53">

3. select u.username, count(m.id) as max from users as u, messages as m where u.id = m.to group by u.username order by max desc limit 1
<img width="219" alt="image" src="https://github.com/ugol-itmo-test/itmo_web_3/assets/103264273/ff3fa41a-ef97-4806-8e0d-87b643e4cba9">


