# Pandas�� matplotlib ���̺귯�� ���� ���ʿ��� ������Ʈ�Դϴ�. 

## ������Ʈ ����
Pandas�� ���� ������ matplotlib�� �ð�ȭ ���ʸ� Ȱ���Ͽ� ����� cctv�� �м��ϴ� ����������Ʈ�Դϴ�. 

## ������Ʈ ����

### Pandas ����
- csv file �б� pd.read_csv()
- excel file �б� pd.read_excel()
- ���� ������ 5�� �б�pd.head()
- ���� ������ 5�� �б� pd.tail()
- ������ �÷��� �����ϱ�  ������������.rename()�Լ�
- Ư�� �÷����� ������ �����ϱ� sort_values(by ='Ư���÷�')
- Ư�� ������ �����ϱ� del ��İ� drop���
- ������ ������躸�� corr() 
- pandas plot�Լ��� �ð�ȭ�ϱ� 
- ������������ ���� ���Ȯ�� �Լ� dataframe.info()
- ������������ ������ ����Ȯ�� dataframe.describe()
- ������������ ��ġ�� merge() �Լ� 
   - on option:  �� �������������� ��ġ�� key��
   - how option: ������������ ��������� ��ġ�� �ɼ�
        - inner: ������
        - outer: ������
        - left: ���� ������������ key������ ���� 
        - right: ������ ������������ key������ ����
- ������������ ����� �ΰ��� ���
   - ��ųʸ��ȿ� ����Ʈ ���
   - ����Ʈ�ȿ� ��ųʸ� ���

### matplotlib ����
- jupyter notebook���� �ѱ۱��� �ذ��ϱ� 
- ��ȭ�� �׸��� plt.figure(figsize=(a, b))
- plot() �� �׷��� �׸���
  - plot(x, y,  color, linestyle, marker, markerfacecolor, markersize, label = '�� �̸�')
     - color: �� ������ ������ �� �ֽ��ϴ�. 
     - linestyle: �� ��� ���� dashed ���� ����
     - marker: ��Ŀ�����  'o' ���׶�̸������ 
     - markerfacecolor: ��Ŀ ���� ����
     - markersize: ��Ŀ ������ ���� 
- plt.grid(True) ��ȭ�� ���ڹ��� �߰��ϱ�
- plt.lenged() �׷��� �� �̸� ��ġ ����
- plt.title() ��ü �׷��� �̸� ����
- plt.xlabel() x�� �̸� ����
- plt.ylabel() y�� �̸� ����
- plt.scatter() �� ������ ������ �׷��� �׸���
    - plt.scatter(x, y, s,  c, marker)
        - s: ��Ŀ ũ�� ����
        - c: ��Ŀ ���� ����
        - marker: ��Ŀ ��缳��
 
