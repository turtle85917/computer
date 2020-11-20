name = '컴퓨터'
try:
    pw = int(input('컴퓨터 비밀번호를 입력하세요 : '))
    while pw != 0000:
        print('잘 못 입력했습니다')
        pw = int(input('컴퓨터 비밀번호를 입력하세요 : '))
    print('컴퓨터 로그인을 성공했습니다!')
    pw = input(f'안녕! 난 {name}야!\n')
    while 1:
        if pw == '종료':
            print(f'{name}: 컴퓨터를 종료할게!')
            print(f'{name}를 종료합니다.')
            break
        if pw == '이름 바꾸기':
            name = input(f'{name}: 내 이름을 멋진 걸로 다시 지어줘!')
        print(f'{name}: {pw}')
        pw = input('')
except Exception as ex:
    print('숫자가 아닌 수를 입력했거나 에러가 났습니다\n{}'.format(ex))
