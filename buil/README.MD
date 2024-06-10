# todo list
LISTBOX : 하루 리스트 만들기

##텍스트 박스에 적은 할 일을 항목추가 버튼을 눌러 리스트 박스에 넣기

버튼 1(항목추가)를 클릭 할 시 텍스트 박스의 글자를 리스트 박스 아이템으로 넣어라
listBox1.Items.Add(textBox1.Text);

textBox1.Clear(); //텍스트 박스 글귀 초기화
textBox1.Focus(); //커서 다시

버튼 2(항목 삭제)를 클릭 할 시 선택한 항목을 삭제
listBox1.Items.RemoveAt(listBox1.SelectedIndex);