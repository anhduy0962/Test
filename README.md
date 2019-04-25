sudo apt-get install libmysqlcppconn-dev
sudo apt-get install libgtkmm-3.0-dev
 sudo apt-get install libgtkmm-3.0


g++ `pkg-config gtkmm-3.0 --cflags --libs` -c GTK.cpp
g++ GTK.o -o GTK `pkg-config gtkmm-3.0 --cflags --libs`
./GTK
