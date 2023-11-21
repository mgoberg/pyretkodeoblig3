include color

#Tegner figur
figur =
  overlay-xy(triangle(500, "solid", "brown"), -300, 0,
    overlay-xy(rectangle(25, 5, "solid", "white"), -490, -770,
    overlay-xy(rectangle(100, 200, "solid", "black"), -490, -650,
      overlay-xy(rectangle(10, 80, "solid", "black"), -425, -520,
          overlay-xy(rectangle(40, 200, "solid", "brown"), -400, -150,
        overlay-xy(rectangle(80, 10, "solid", "black"), -390, -555,
          overlay-xy(rectangle(80, 80, "solid", "sky-blue"), -390, -520,
            overlay-xy(rectangle(90, 90, "solid", "white"), -385, -515,
                  overlay-xy(rectangle(400, 500, "solid", "orange"), -350, -350,
                    (rectangle(1100, 800, "solid",  "white")))))))))))

#Printer figur
figur
