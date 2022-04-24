# ������ "API_final_yatube"

## ��������

������ �������� � ���� ���������� ��� ������ ���������� � ����������� **Yatube** ����� API, ������� ��������� ��������� ��������� ����������, ����������� � ���, ��� ����� ����� �������� �������� � ������� �� ������ ��� ��� ���� ����������.

�� ������� �������� �������� � view-������� ���������� posts.

������������������� ������������� ��������� ��������� � �������� ������ ��������, � ��������� ������� ������ ��������������� ������ ��� ������.

����� �� ��������� ������, �� ������ [Redoc](http://127.0.0.1:8000/redoc/) ����� �������� ������������ ��� API Yatube. � ��� ��������� �������� ���������������� API. ������������ � ������� **Redoc**.

## ���������

����������� ����������� � ������� � ���� � ��������� ������:

```text
git clone git@github.com:Chuvichkin/api_final_yatube.git
```

```text
cd api_final_yatube
```

C������ � ������������ ����������� ���������:

```text
python -m venv venv
```

```text
source venv/Scripts/activate
```

����������/�������� pip � ����������� �� ����� requirements.txt:

```text
python -m pip install --upgrade pip
```

```text
pip install -r requirements.txt
```

������� � ���������� � manage.py � ���������� ��������:

```text
cd yatube_api
```

```text
python manage.py migrate
```

��������� ������:

```text
python manage.py runserver
```

## ������� �������� � API.

### ��������� �����������

��������� ���� ������������ � ����������.

```text
http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/
```

�����:

```text
{
"id": 0,
"author": "string",
"text": "string",
"created": "2019-08-24T14:15:22Z",
"post": 0
}
```

������ ������ �������� ���������� �� ������ [Redoc](http://127.0.0.1:8000/redoc/).
