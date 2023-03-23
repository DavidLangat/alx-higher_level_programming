Python - Object-relational mapping

Before you start…
Please make sure your MySQL server is in 8.0 -> How to install MySQL 8.0 in Ubuntu 20.04

Background Context
In this project, you will link two amazing worlds: Databases and Python!

In the first part, you will use the module MySQLdb to connect to a MySQL database and execute your SQL queries.

In the second part, you will use the module SQLAlchemy (don’t ask me how to pronounce it…) an Object Relational Mapper (ORM).

The biggest difference is: no more SQL queries! Indeed, the purpose of an ORM is to abstract the storage to the usage. With an ORM, your biggest concern will be “What can I do with my objects” and not “How this object is stored? where? when?”. You won’t write any SQL queries only Python code. Last thing, your code won’t be “storage type” dependent. You will be able to change your storage easily without re-writing your entire project.


0-select_states.py                      11-model_state_insert.py                4-cities_by_state.py                  1-filter_states.py                      12-model_state_update_id_2.py           5-filter_cities.py                      model_city.py 10-model_state_my_get.py                13-model_state_delete_a.py              6-model_state.py                        model_state.py 100-relationship_states_cities.py       14-model_city_fetch_by_state.py         7-model_state_fetch_all.py              relationship_city.py 101-relationship_states_cities_list.py  2-my_filter_states.py                   8-model_state_fetch_first.py            relationship_state.py 102-relationship_cities_states_list.py  3-my_safe_filter_states.py              9-model_state_filter_a.py  