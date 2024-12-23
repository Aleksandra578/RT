# RT
RT
Реальный кейс от компании «Ростелеком Информационные Технологии»
Задачи по тестированию сайта "Ростелеком":
- протестировать требования;
- разработать тест-кейсы (не менее 15);
- провести автоматизированное тестирование продукта (по одному автотесту на каждый тест-кейс);
- описать обнаруженные дефекты.
Проект выполнен с использованием: PageObject, Selenium и PyTest.
Тест кейсы, баг репорты и тестирование требований находятся по ссылке https://docs.google.com/spreadsheets/d/1gUiQ-v6tOwsLIkuJ3h5IVwPqc4nOVSW1V-N2rybDQEA/edit?usp=sharing
Запуск тестов при помощи команд в консоли:
python -m pytest -v --driver Edge --driver-path msedgedriver.exe tests/test_auth_page.py python -m pytest -v --driver Edge --driver-path msedgedriver.exe tests/test_registr_page.py
