select *
from cars_info 

select cast(make as varchar)
from cars_info

select distinct fuel_type
from cars_info

select min(length) as min_length,
max(length) as max_length
from cars_info 

select * 
from cars_info
where body_style is null;

UPDATE cars_info
SET num_of_doors = 'four'
WHERE make = 'dodge';
UPDATE cars_info
SET num_of_doors = 'four'
WHERE make = 'mazda';

select min(price) as min_price,
max(price) as max_price
from cars_info

select distinct num_of_cylinders
from cars_info

update
cars_info
set num_of_cylinders = 'two'
where num_of_cylinders = 'tow';



select min(compression_ratio) as min_compression_ratio,
max(compression_ratio) as max_compression_ratio
from cars_info
where compression_ratio <> 70

select count (*) as num_of_rows_to_delete
delete from cars_info
where compression_ratio = 70;

update cars_info
set drive_wheels =trim(drive_wheels)
where true

