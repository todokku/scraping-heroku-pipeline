# scraping-heroku-pipeline
working for Python3 on Heroku


## �ړI
Docker�w�K���ł�Python���G���Ă݂�B
�@�\�̓X�N���C�s���O�B

## �����
�J�����̓��[�J���œ�������悤��Docker�R���e�i�ŁB
�����[�X����Heroku�ŁB

### Heroku
Scheduler�̂݁B�����œ������B

## Heroku�p�̊��\�z
LINE�ւ̒ʒm�g�[�N�����A�ȉ��̊��ϐ��ɐݒ肷��B
LINE_NOTIFY_TOKEN=****

## ����
docker build -t scraping .
docker run --name test --env-file ../line_api_key scraping


