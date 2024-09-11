TEST RUN INSTRUCTION:
1. Install requirements:
pip install -r requirements.txt

2. Run all tests:
pytest -v

3. Generate allure report
pytest tests.py --alluredir=allure_results

4. Watch allure report in html
allure serve allure_results

Project files and description:
File name	File Content
test_create_courier.py	Courier Creation Tests
test_get_order_list.py	Getting Order List Test
test_login_courier.py	Login Courier Tests
test_make_order.py	Create Order Tests
conftest.py	Project system file
generators.py	Random order data Gens
data.py	Project data file
requirements.txt	Proj. req. file
allure_results.dir	Allure reports dir