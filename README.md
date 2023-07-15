# verbose-octo-giggle
class AssertionError (Exception):
    pass
class ValueError (Exception):
    pass
class LizardInLemonadeMug (Exception):
    pass
class BarBurntDown (Exception):
    pass
class Zerro(Exception):
    pass
class bar (Exception):
    pass
def anekdot():
    try:
        znah = (input(' сколько кружек вы хотите закозать дорогой гость ?'))
        if znah == "ящериццу в стакан":
            raise ValueError
        if znah == " где туалет?":
            raise bar
        if  znah=="qwerty":
             raise LizardInLemonadeMug
        znah = int(znah)
        if znah ==999999999 :
            raise AssertionError
        if znah ==-1:
            raise LizardInLemonadeMug
        if znah ==0:
            raise Zerro
        print(' вы получи свою кружку лимонада')
    except AssertionError:
        print(' мы не можем выдать слишком много кружек лимонада')
    except LizardInLemonadeMug:
        print('мы взамешательстве как мы вам сможем так выдать')
    except Zerro:
        print('хорошо получите то с чем и пришли то есть не счем)')
    except ValueError:
        print(' у нас закончились ящерицы мы их съели')
    except bar:
        print('он сгорел его сжег Joker')
    anekdot()
anekdot()
