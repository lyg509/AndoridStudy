#  Widget
##  01 Text는 텍스트를 표시하거나 편집할 수 있는 위젯이다. 편집 기능을 제외한 주요 속성으로 text, textColor, textSize, typeface, textStyle, textAppearance, letterSpacing, lineSpacingExtra, lineSpacingMultiplier, gravity, autoLink, singleLine, elipsize, drawableTop, drawableBotom, drawableLeft, drawableRight, drawablepadding 이 있다.
#  
##  02 CheckedTextView는 TextView에 체크 표시 기능을 추가한 위젯이다. 주요 속성으로 checked, checkMark가 있다.
#  
##  03 EditText는 텍스트를 편집할 수 있도록 TextView의 기본 속성을 변경한 위젯이다. 주요 속성으로 hint, ems. lines, maxLength, selectAllOnFocus, digits, inputType이 있다.
#  
##  04 CheckBox는 체크와 언체크 두 가지 상태를 가지는 버튼이다. 주요 메서드로 isChecked(), set-Checked(),toggle()이 있다.
#  
##  05 RadioButton은 여러 옵션 중 하나만 선택해야 할 때 사용한다. 흔히 라디오 그룹에 묶어서 활용하며 라디오 그룹 내에 가로 또는 세로 방향으로 배치할 수 있다.
#  
##  06 ToggleButton은 On/Off 두 가지 상태를 가지는 버튼이다. 상태에 따라 서로 다른 텍스트와 지시자를 표시할 수 있으며, CheckBox와 마찬가지로 isChecked(), setChecked(), toggle()메서드를 사용할 수 있다.
#   
##  07 ImageView는 리소스, 로컬 파일, Bitmap, Drawable을 출력할 수 있는 위젯이다. 주요 속성으로 src, scaleType, adjustViewBounds, maxWidth, maxHeight, cropToPadding이 있다.
#  
##  08 ImageButton은 버튼처럼 누르고 뗴는 효과를 ImageView에 추가한 위젯이다.
#  
##  09 ProgressBar는 작업의 진행 상황을 회전 바퀴나 수평 막대로 보여주며, 확정 모드와 불확정 모드가 제공된다.
#  
##  10 RatingBar는 별의 개수로 평점을 입력받는다.
#  
##  11 SeekBar는 프로그레스바의 일종으로 썸을 이용해 사용자가 진행값을 조작할 수 있다. 썸을 조작하면 이벤트가 발생하는데 SeekBar.OnSeekbarChangeListener 인터페이스 객체를 통해 처리할 수 있다.
SeekBar.OnSeekBarChangeListener 인터페이스에 포함된 추상 메서드로는 onStartTracking-Touch(), onProgressChanged(),  onStopTrackingTouch()가 있다.

