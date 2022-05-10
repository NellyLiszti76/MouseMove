# MouseMove
; Variant 1 : set coordinates directly MouseMove(700,700, 0) ; starting position MouseMove(10,100, 50) ; speed set to 50 so you can see the effect  ; Variant 2 : coordinates as array Local $aPoint1[2] = [700, 700] Local $aPoint2[2] = [10, 100] MouseMove($aPoint1[0], $aPoint1[1], 0) MouseMove($aPoint2[0], $aPoint2[1], 50)
