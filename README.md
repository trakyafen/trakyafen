<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Element Bul</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        #periyodik-tablo {
            display: grid;
            grid-template-columns: repeat(18, 1fr);
            gap: 2px;
            margin: 20px auto;
            width: 90%;
        }
        .element {
            border: 1px solid #000;
            padding: 10px;
            text-align: center;
            cursor: pointer;
        }
        .element:hover {
            background-color: lightgray;
        }
        .element-bilgi {
            display: none;
        }
        .element-bilgi.active {
            display: block;
        }
        .element-bilgi p {
            text-align: left;
            margin: 0 20%;
        }
        .group1 {
            background-color: purple;
        }
        .group2 {
            background-color: #e0b0ff;
        }
        .group3 {
            background-color: #7F7FFF;
        }
        .group4 {
            background-color: green;
        }
        .group5 {
            background-color: yellow;
        }
        .group6 {
            background-color: #B7A793;
        }
        .group7 {
            background-color: #FF7F00;
        }
        .group8 {
            background-color: #66ff00;
        }
        .group9 {
            background-color: #ff0000;
        }
        .group10 {
            background-color: #30d5c8;
        }
        .group11 {
            background-color: purple;
           width: 100;
        }
        .group12 {
            background-color: #e0b0ff;
        }
        .group13 {
            background-color: #7F7FFF;
        }
        .group14 {
            background-color: green;
        }
        .group15 {
            background-color: yellow;
        }
        .group16 {
            background-color: #B7A793;
        }
        .group17 {
            background-color: #FF7F00;
        }
        .group18 {
            background-color: #66ff00;
        }
        .group19 {
            background-color: #ff0000;
        }
        .group20 {
            background-color: #30d5c8;
        }
        .daha-fazlasi-icin-tiklayin {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .daha-fazlasi-icin-tiklayin:hover {
            background-color: #0056b3;
        }
        @media only screen and (max-width: 600px) {
            #periyodik-tablo {
                display: none;
            }
            #element-list {
                display: flex;
                flex-direction: column;
                padding: 0;
                margin: 0;
                list-style-type: none;
            }
            #element-list li {
                padding: 10px;
                border-bottom: 1px solid #ccc;
                cursor: pointer;
            }
            #element-list li:last-child {
                border-bottom: none;
            }
            #element-list li:nth-child(odd) {
                background-color: #f9f9f9;
            }
            .mobile-container {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
            }
            .mobile-container .element {
                flex: 0 0 20%; /* Her bir elementin genişliğini ayarlar */
                margin: 1%; /* Elementler arasındaki boşluğu ayarlar */
            }
        }
        @media (min-width: 601px) {
            #element-list {
                display: none;
            }
            #element-container {
                display: block;
            }
            #categories {
                display: none;
            }
            .mobile-container {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div id="ana-sayfa">
        <h1>Periyodik Tablo</h1>
        <p>Bu sitede periyodik tablodaki elementleri ve özelliklerini bulabilirsiniz.</p>
    </div>

    <div id="periyodik-tablo">
        <div class="element group6" id="hidrojen">H<br>1</div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>

<div class="element group1" style="cursor: default; pointer-events: none;">Alkali Metaller</div>
        <div class="element group2" style="cursor: default; pointer-events: none;">Toprak Alkali Metaller</div>
<div class="element group3" style="cursor: default; pointer-events: none;">Geçiş Metalleri</div>
<div class="element group4" style="cursor: default; pointer-events: none;">Yarı Metaller</div>
<div class="element group5" style="cursor: default; pointer-events: none;">Halojenler</div>

       
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>


        
        <div></div>
        <div></div>
        
        <div class="element group10" id="helyum" >He<br>2</div>




        <div class="element group1" id="lityum">Li<br>3</div>
        <div class="element group2" id="berilyum">Be<br>4</div>
        <div></div>
        <div></div>
        <div></div>

 <div class="element group6" style="cursor: default; pointer-events: none;">Ametaller</div>
<div class="element group7" style="cursor: default; pointer-events: none;">Metaller</div>
<div class="element group10" style="cursor: default; pointer-events: none;">Soygazlar</div>
<div class="element group8" style="cursor: default; pointer-events: none;">Lantanitler</div>
<div class="element group9" style="cursor: default; pointer-events: none;">Aktinitler</div>

        <div></div>
        <div></div>
        
      

        <div class="element group4" id="bor">B<br>5</div>
        <div class="element group6" id="karbon">C<br>6</div>
        <div class="element group6" id="azot">N<br>7</div>
        <div class="element group6" id="oksijen">O<br>8</div>
        <div class="element group5"id="flor">F<br>9</div>
        <div class="element group10" id="neon">Ne<br>10</div>
        <div class="element group1" id="sodyum">Na<br>11</div>
        <div class="element group2" id="magnezyum">Mg<br>12</div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>

        <div class="element group7" id="aluminyum">Al<br>13</div>
     

        <div class="element group4" id="silisyum">Si<br>14</div>
        <div class="element group6" id="fosfor">P<br>15</div>
        <div class="element group6" id="kükürt">S<br>16</div>
        <div class="element group5" id="klor">Cl<br>17</div>
        <div class="element group10" id="argon">Ar<br>18</div>
        <div class="element group1" id="potasyum">K<br>19</div>
        <div class="element group2" id="kalsiyum">Ca<br>20</div>
        <div class="element group3" id="skandiyum">Sc<br>21</div>
        <div class="element group3" id="titanyum">Ti<br>22</div>
        <div class="element group3" id="vanadyum">V<br>23</div>
        <div class="element group3" id="krom">Cr<br>24</div>
        <div class="element group3" id="manganez">Mn<br>25</div>
        <div class="element group3" id="demir">Fe<br>26</div>
        <div class="element group3" id="kobalt">Co<br>27</div>
        <div class="element group3" id="nikel">Ni<br>28</div>
        <div class="element group3" id="bakır">Cu<br>29</div>
        <div class="element group3" id="çinko">Zn<br>30</div>
        <div class="element group7" id="galyum">Ga<br>31</div>
        <div class="element group4" id="germanyum">Ge<br>32</div>
        <div class="element group4" id="arsenik">As<br>33</div>
        <div class="element group6" id="selen">Se<br>34</div>
        <div class="element group5" id="brom">Br<br>35</div>
        <div class="element group10" id="kripton">Kr<br>36</div>
        <div class="element group1" id="rubidyum">Rb<br>37</div>
        <div class="element group2" id="stronsiyum">Sr<br>38</div>
        <div class="element group3" id="itriyum">Y<br>39</div>
        <div class="element group3" id="zirkonyum">Zr<br>40</div>
        <div class="element group3" id="niobyum">Nb<br>41</div>
        <div class="element group3" id="molybden">Mo<br>42</div>
        <div class="element group3" id="teknetiyum">Tc<br>43</div>
        <div class="element group3" id="rutenyum">Ru<br>44</div>
        <div class="element group3" id="rhodium">Rh<br>45</div>
        <div class="element group3" id="paladyum">Pd<br>46</div>
        <div class="element group3" id="gümüş">Ag<br>47</div>
        <div class="element group3" id="kadmiyum">Cd<br>48</div>
        <div class="element group7" id="indiyum">In<br>49</div>
        <div class="element group7" id="kalay">Sn<br>50</div>
        <div class="element group4" id="antimon">Sb<br>51</div>
        <div class="element group4" id="tellur">Te<br>52</div>
        <div class="element group5" id="iyot">I<br>53</div>
        <div class="element group10" id="ksenon">Xe<br>54</div>
        <div class="element group1" id="sezyum">Cs<br>55</div>
        <div class="element group2" id="baryum">Ba<br>56</div>
        <div class="element group8"><br>*</div>
       
        <div class="element group3" id="hafniyum">Hf<br>72</div>
        <div class="element group3" id="tantal">Ta<br>73</div>
        <div class="element group3" id="tungsten">W<br>74</div>
        <div class="element group3" id="renyum">Re<br>75</div>
        <div class="element group3" id="osmiyum">Os<br>76</div>
        <div class="element group3" id="iridyum">Ir<br>77</div>
        <div class="element group3" id="platin">Pt<br>78</div>
        <div class="element group3" id="altın">Au<br>79</div>
        <div class="element group3"id="cıva">Hg<br>80</div>
        <div class="element group7" id="talium">Tl<br>81</div>
        <div class="element group7" id="kurşun">Pb<br>82</div>
        <div class="element group7" id="bizmut">Bi<br>83</div>
        <div class="element group4" id="polonyum">Po<br>84</div>
        <div class="element group5" id="astatin">At<br>85</div>
        <div class="element group10" id="radon">Rn<br>86</div>
        <div class="element group1" id="fransiyum">Fr<br>87</div>
        <div class="element group2" id="radyum">Ra<br>88</div>
        <div class="element group9"><br>**</div>
                <div class="element group3" id="rutherfordiyum">Rf<br>104</div>
        <div class="element group3" id="dubniyum">Db<br>105</div>
        <div class="element group3" id="seaborgiyum">Sg<br>106</div>
        <div class="element group3" id="bohriyum">Bh<br>107</div>
        <div class="element group3" id="hassium">Hs<br>108</div>
        <div class="element group3" id="meitneriyum">Mt<br>109</div>
        <div class="element group3" id="darmstadtiyum">Ds<br>110</div>
        <div class="element group3" id="roentgeniyum">Rg<br>111</div>
        <div class="element group3"id="kopernikiyum">Cn<br>112</div>
        <div class="element group7" id="nihonyum">Nh<br>113</div>
        <div class="element group7" id="floroviyum">Fl<br>114</div>
        <div class="element group7" id="moskoviyum">Mc<br>115</div>
        <div class="element group7" id="livermoryum">Lv<br>116</div>
        <div class="element group5" id="tenessiyum">Ts<br>117</div>
        <div class="element group10" id="oganesson">Og<br>118</div>
<div></div>


        <div class="element group8"><br>*</div>
<div class="element group8" id="lantan">La<br>57</div>
        <div class="element group8" id="sezyum">Ce<br>58</div>
        <div class="element group8" id="praseodimyum">Pr<br>59</div>
        <div class="element group8" id="neodimyum">Nd<br>60</div>
        <div class="element group8" id="prometyum">Pm<br>61</div>
        <div class="element group8" id="samaryum">Sm<br>62</div>
        <div class="element group8" id="europyum">Eu<br>63</div>
        <div class="element group8" id="gadolinyum">Gd<br>64</div>
        <div class="element group8" id="terbium">Tb<br>65</div>
        <div class="element group8" id="disprosiyum">Dy<br>66</div>
        <div class="element group8" id="holmiyum">Ho<br>67</div>
        <div class="element group8" id="erbyum">Er<br>68</div>
        <div class="element group8" id="tulyum">Tm<br>69</div>
        <div class="element group8"id="iteryum">Yb<br>70</div>
        <div class="element group8" id="lutesyum">Lu<br>71</div>
   <div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
<div></div>
        <div class="element group9"><br>*</div>

 <div class="element group9" id="aktinyum">Ac<br>89</div>
        <div class="element group9" id="toryum">Th<br>90</div>
        <div class="element group9" id="protaktinyum">Pa<br>91</div>
        <div class="element group9" id="uranyum">U<br>92</div>
        <div class="element group9" id="neptünyum">Np<br>93</div>
        <div class="element group9" id="plütonyum">Pu<br>94</div>
        <div class="element group9" id="amerikyum">Am<br>95</div>
        <div class="element group9" id="küriyum">Cm<br>96</div>
        <div class="element group9" id="berkelyum">Bk<br>97</div>
        <div class="element group9" id="kaliforniyum">Cf<br>98</div>
        <div class="element group9" id="aynştaynyum">Es<br>99</div>
        <div class="element group9" id="fermiyum">Fm<br>100</div>
        <div class="element group9" id="mendelevyum">Md<br>101</div>
        <div class="element group9" id="nobeliyum">No<br>102</div>
        <div class="element group9" id="lawrensiyum">Lr<br>103</div>

    </div>
    <div class="mobile-container">
        <!-- Alkali metallerden aktinitlere kadar olan elemanlar -->
        <div class="element group1">Alkali Metaller</div>
        <div class="element group2">Toprak Alkali Metaller</div>
        <div class="element group3">Geçiş Metalleri</div>
        <div class="element group4">Yarı Metaller</div>
        <div class="element group5">Halojenler</div>
        <div class="element group6">Ametaller</div>
        <div class="element group7">Metaller</div>
        <div class="element group10">Soygazlar</div>
        <div class="element group8">Lantanitler</div>
        <div class="element group9">Aktinitler</div>
    </div>
    <ul id="element-list">
     
        <div class="element group6" id="hidrojen">H<br>1</div>
        <div class="element group10" id="helyum">He<br>2</div>
          <div class="element group1" id="lityum">Li<br>3</div>
          <div class="element group2" id="berilyum">Be<br>4</div>	
       <div class="element group4" id="bor">B<br>5</div>
          <div class="element group6" id="karbon">C<br>6</div>
          <div class="element group6" id="azot">N<br>7</div>
          <div class="element group6" id="oksijen">O<br>8</div>
          <div class="element group5" id="flor">F<br>9</div>
          <div class="element group10" id="neon">Ne<br>10</div>
          <div class="element group1" id="sodyum">Na<br>11</div>
          <div class="element group2" id="magnezyum">Mg<br>12</div>
        <div class="element group7" id="aluminyum">Al<br>13</div>
        <div class="element group4" id="silisyum">Si<br>14</div>
        <div class="element group6" id="fosfor">P<br>15</div>
        <div class="element group6" id="kükürt">S<br>16</div>
        <div class="element group5" id="klor">Cl<br>17</div>
        <div class="element group10" id="argon">Ar<br>18</div>
        <div class="element group1" id="potasyum">K<br>19</div>
        <div class="element group2" id="kalsiyum">Ca<br>20</div>
        <div class="element group3" id="skandiyum">Sc<br>21</div>
        <div class="element group3" id="titanyum">Ti<br>22</div>
        <div class="element group3" id="vanadyum">V<br>23</div>
        <div class="element group3" id="krom">Cr<br>24</div>
        <div class="element group3" id="manganez">Mn<br>25</div>
        <div class="element group3" id="demir">Fe<br>26</div>
        <div class="element group3" id="kobalt">Co<br>27</div>
        <div class="element group3" id="nikel">Ni<br>28</div>
        <div class="element group3" id="bakır">Cu<br>29</div>
        <div class="element group3" id="çinko">Zn<br>30</div>
        <div class="element group7" id="galyum">Ga<br>31</div>
        <div class="element group4" id="germanyum">Ge<br>32</div>
        <div class="element group4" id="arsenik">As<br>33</div>
        <div class="element group6" id="selen">Se<br>34</div>
        <div class="element group5" id="brom">Br<br>35</div>
        <div class="element group10" id="kripton">Kr<br>36</div>
        <div class="element group1" id="rubidyum">Rb<br>37</div>
        <div class="element group2" id="stronsiyum">Sr<br>38</div>
        <div class="element group3" id="itriyum">Y<br>39</div>
        <div class="element group3" id="zirkonyum">Zr<br>40</div>
        <div class="element group3" id="niobyum">Nb<br>41</div>
        <div class="element group3" id="molibden">Mo<br>42</div>
        <div class="element group3" id="teknetsiyum">Tc<br>43</div>
        <div class="element group3" id="rutenyum">Ru<br>44</div>
        <div class="element group3" id="rhodiyum">Rh<br>45</div>
        <div class="element group3" id="paladyum">Pd<br>46</div>
        <div class="element group3" id="gümüş">Ag<br>47</div>
        <div class="element group3" id="kadmiyum">Cd<br>48</div>
        <div class="element group7" id="indiyum">In<br>49</div>
        <div class="element group7" id="kalay">Sn<br>50</div>
        <div class="element group4" id="antimon">Sb<br>51</div>
        <div class="element group6" id="tellur">Te<br>52</div>
        <div class="element group5" id="iyot">I<br>53</div>
        <div class="element group10" id="ksenon">Xe<br>54</div>
        <div class="element group1" id="sezyum">Cs<br>55</div>
        <div class="element group2" id="baryum">Ba<br>56</div>
        <div class="element group8" id="lantan">La<br>57</div>
        <div class="element group8" id="seryum">Ce<br>58</div>
        <div class="element group8" id="praseodim">Pr<br>59</div>
        <div class="element group8" id="neodim">Nd<br>60</div>
        <div class="element group8" id="prometyum">Pm<br>61</div>
        <div class="element group8" id="samaryum">Sm<br>62</div>
        <div class="element group8" id="evropiyum">Eu<br>63</div>
        <div class="element group8" id="gadolinyum">Gd<br>64</div>
        <div class="element group8" id="terbiyum">Tb<br>65</div>
        <div class="element group8" id="disprozyum">Dy<br>66</div>
        <div class="element group8" id="holmiyum">Ho<br>67</div>
        <div class="element group8" id="erbiyum">Er<br>68</div>
        <div class="element group8" id="tulyum">Tm<br>69</div>
        <div class="element group8" id="iteryum">Yb<br>70</div>
        <div class="element group8" id="lütesyum">Lu<br>71</div>
        <div class="element group9" id="aktinyum">Ac<br>89</div>
        <div class="element group9" id="toryum">Th<br>90</div>
        <div class="element group9" id="proaktinyum">Pa<br>91</div>
        <div class="element group9" id="uranyum">U<br>92</div>
        <div class="element group9" id="neptünyum">Np<br>93</div>
        <div class="element group9" id="plutonyum">Pu<br>94</div>
        <div class="element group9" id="amerikyum">Am<br>95</div>
        <div class="element group9" id="küriyum">Cm<br>96</div>
        <div class="element group9" id="berkyum">Bk<br>97</div>
        <div class="element group9" id="kaliforniyum">Cf<br>98</div>
        <div class="element group9" id="einsteinyum">Es<br>99</div>
        <div class="element group9" id="fermiyum">Fm<br>100</div>
        <div class="element group9" id="mendelevyum">Md<br>101</div>
        <div class="element group9" id="nobeliyum">No<br>102</div>
        <div class="element group9" id="lawrensiyum">Lr<br>103</div>
        <div class="element group3" id="rutherfordyum">Rf<br>104</div>
        <div class="element group3" id="dubniyum">Db<br>105</div>
        <div class="element group3" id="seaborgiyum">Sg<br>106</div>
        <div class="element group3" id="bohriyum">Bh<br>107</div>
        <div class="element group3" id="hassium">Hs<br>108</div>
        <div class="element group3" id="meitneriyum">Mt<br>109</div>
        <div class="element group3" id="darmstadtiyum">Ds<br>110</div>
        <div class="element group3" id="roentgenyum">Rg<br>111</div>
        <div class="element group3" id="kopernikyum">Cn<br>112</div>
        <div class="element group7" id="nihonyum">Nh<br>113</div>
        <div class="element group7" id="flerovyum">Fl<br>114</div>
        <div class="element group7" id="moskovyum">Mc<br>115</div>
        <div class="element group7" id="livermoryum">Lv<br>116</div>
        <div class="element group5" id="tenessiyum">Ts<br>117</div>
        <div class="element group10" id="oganesson">Og<br>118</div>
    </ul>

    <div id="element-bilgileri">
        <div class="element-bilgi" id="hidrojen-bilgi">
            <h2>Hidrojen (H)</h2>
            <p>Atom Numarası: 1</p>
            <p>Atom Kütlesi: 1.008</p>
            <p>Grup: 1</p>
            <p>Periyot: 1</p>
            <p>Blok: s</p>
            <p>Özellikler: Hidrojen, evrendeki en bol elementtir ve genellikle renksiz, kokusuz bir gaz olarak bulunur.</p>
    <a href="https://tr.wikipedia.org/wiki/Hidrojen" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
        </div>
        <div class="element-bilgi" id="helyum-bilgi">
            <h2>Helyum (He)</h2>
            <p>Atom Numarası: 2</p>
            <p>Atom Kütlesi: 4.0026</p>
            <p>Grup: 18</p>
            <p>Periyot: 1</p>
            <p>Blok: s</p>
            <p>Özellikler: Helyum, renksiz ve kokusuz bir asal gazdır. Balonlarda ve hava gemilerinde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Helyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
        </div>
    <div class="element-bilgi" id="lityum-bilgi">
        <h2>Lityum (Li)</h2>
        <p>Atom Numarası: 3</p>
        <p>Atom Kütlesi: 6.94</p>
        <p>Grup: 1</p>
        <p>Periyot: 2</p>
        <p>Blok: s</p>
        <p>Özellikler: Lityum, metalik özelliklere sahip yumuşak bir katıdır ve sudan çözülebilen bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Lityum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="berilyum-bilgi">
        <h2>Berilyum (Be)</h2>
        <p>Atom Numarası: 4</p>
        <p>Atom Kütlesi: 9.0122</p>
        <p>Grup: 2</p>
        <p>Periyot: 2</p>
        <p>Blok: s</p>
        <p>Özellikler: Berilyum, hafif, sert, gri-çelik renkte bir metaldir ve genellikle alaşımlar halinde bulunur.</p>
    <a href="https://tr.wikipedia.org/wiki/Berilyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="bor-bilgi">
        <h2>Bor (B)</h2>
        <p>Atom Numarası: 5</p>
        <p>Atom Kütlesi: 10.81</p>
        <p>Grup: 13</p>
        <p>Periyot: 2</p>
        <p>Blok: p</p>
        <p>Özellikler: Bor, katı bir elementtir ve saf formda kristal yapılıdır. Yarı iletken özellik gösterir.</p>
    <a href="https://tr.wikipedia.org/wiki/Bor" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="karbon-bilgi">
        <h2>Karbon (C)</h2>
        <p>Atom Numarası: 6</p>
        <p>Atom Kütlesi: 12.011</p>
        <p>Grup: 14</p>
        <p>Periyot: 2</p>
        <p>Blok: p</p>
        <p>Özellikler: Karbon, tüm yaşam formlarının temel yapı taşıdır ve çeşitli allotropları vardır (elmas, grafit, fulerenler).</p>
    <a href="https://tr.wikipedia.org/wiki/Karbon" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="azot-bilgi">
        <h2>Azot (N)</h2>
        <p>Atom Numarası: 7</p>
        <p>Atom Kütlesi: 14.007</p>
        <p>Grup: 15</p>
        <p>Periyot: 2</p>
        <p>Blok: p</p>
        <p>Özellikler: Azot, atmosferdeki en bol gazlardan biridir ve birçok biyolojik süreçte önemli bir rol oynar.</p>
    <a href="https://tr.wikipedia.org/wiki/Azot" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="oksijen-bilgi">
        <h2>Oksijen (O)</h2>
        <p>Atom Numarası: 8</p>
        <p>Atom Kütlesi: 15.999</p>
        <p>Grup: 16</p>
        <p>Periyot: 2</p>
        <p>Blok: p</p>
        <p>Özellikler: Oksijen, atmosferdeki en yaygın elementtir ve birçok yaşam formu için hayati öneme sahip olan bir gazdır.</p>
    <a href="https://tr.wikipedia.org/wiki/Oksijen" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="flor-bilgi">
        <h2>Flor (F)</h2>
        <p>Atom Numarası: 9</p>
        <p>Atom Kütlesi: 18.998</p>
        <p>Grup: 17</p>
        <p>Periyot: 2</p>
        <p>Blok: p</p>
        <p>Özellikler: Flor, zehirli ve reaktif bir gazdır. Diş macunları ve su arıtma sistemlerinde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Flor" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="neon-bilgi">
        <h2>Neon (Ne)</h2>
        <p>Atom Numarası: 10</p>
        <p>Atom Kütlesi: 20.180</p>
        <p>Grup: 18</p>
        <p>Periyot: 2</p>
        <p>Blok: p</p>
        <p>Özellikler: Neon, renksiz, kokusuz ve inert bir gazdır. Reklam panolarında ve lambalarda yaygın olarak kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Neon" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="sodyum-bilgi">
        <h2>Sodyum (Na)</h2>
        <p>Atom Numarası: 11</p>
        <p>Atom Kütlesi: 22.990</p>
        <p>Grup: 1</p>
        <p>Periyot: 3</p>
        <p>Blok: s</p>
        <p>Özellikler: Sodyum, havada kolayca oksitlenen yumuşak bir metaldir ve su ile şiddetli reaksiyona girer.</p>
    <a href="https://tr.wikipedia.org/wiki/Sodyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="magnezyum-bilgi">
        <h2>Magnezyum (Mg)</h2>
        <p>Atom Numarası: 12</p>
        <p>Atom Kütlesi: 24.305</p>
        <p>Grup: 2</p>
        <p>Periyot: 3</p>
        <p>Blok: s</p>
        <p>Özellikler: Magnezyum, hafif, parlak bir gümüş renkli bir metaldir ve yanıcı bir şekilde yanar.</p>
    <a href="https://tr.wikipedia.org/wiki/Magnezyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="aluminyum-bilgi">
        <h2>Alüminyum (Al)</h2>
        <p>Atom Numarası: 13</p>
        <p>Atom Kütlesi: 26.982</p>
        <p>Grup: 13</p>
    <p>Periyot: 3</p>
    <p>Blok: p</p>
    <p>Özellikler: Alüminyum, hafif, yumuşak, metalik grimsi bir renge sahip bir metaldir ve birçok alaşımın ana bileşenidir.</p>
    <a href="https://tr.wikipedia.org/wiki/Aluminyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="silisyum-bilgi">
        <h2>Silisyum (Si)</h2>
        <p>Atom Numarası: 14</p>
        <p>Atom Kütlesi: 28.085</p>
        <p>Grup: 14</p>
        <p>Periyot: 3</p>
        <p>Blok: p</p>
        <p>Özellikler: Silisyum, gri bir renk alan, katı bir metaloiddir ve doğada en yaygın bulunan elementlerden biridir.</p>
    <a href="https://tr.wikipedia.org/wiki/Silisyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="fosfor-bilgi">
        <h2>Fosfor (P)</h2>
        <p>Atom Numarası: 15</p>
        <p>Atom Kütlesi: 30.974</p>
        <p>Grup: 15</p>
        <p>Periyot: 3</p>
        <p>Blok: p</p>
        <p>Özellikler: Fosfor, katı bir elementtir ve çeşitli formlarda bulunur. Biyolojik sistemlerde hayati bir rol oynar.</p>
    <a href="https://tr.wikipedia.org/wiki/Fosfor" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="kükürt-bilgi">
        <h2>Kükürt (S)</h2>
        <p>Atom Numarası: 16</p>
        <p>Atom Kütlesi: 32.06</p>
        <p>Grup: 16</p>
        <p>Periyot: 3</p>
        <p>Blok: p</p>
        <p>Özellikler: Kükürt, katı bir elementtir ve doğada genellikle mineral formunda veya elementel olarak bulunur.</p>
    <a href="https://tr.wikipedia.org/wiki/Kükürt" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="klor-bilgi">
        <h2>Klor (Cl)</h2>
        <p>Atom Numarası: 17</p>
        <p>Atom Kütlesi: 35.45</p>
        <p>Grup: 17</p>
        <p>Periyot: 3</p>
        <p>Blok: p</p>
        <p>Özellikler: Klor, soluk sarımsı-yeşil bir renge sahip olan ve çok reaktif olan bir gazdır.</p>
    <a href="https://tr.wikipedia.org/wiki/Klor" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="argon-bilgi">
        <h2>Argon (Ar)</h2>
        <p>Atom Numarası: 18</p>
        <p>Atom Kütlesi: 39.948</p>
        <p>Grup: 18</p>
        <p>Periyot: 3</p>
        <p>Blok: p</p>
        <p>Özellikler: Argon, renksiz, kokusuz ve inert bir gazdır. Ampullerde ve ark kaynaklarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Argon" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="potasyum-bilgi">
        <h2>Potasyum (K)</h2>
        <p>Atom Numarası: 19</p>
        <p>Atom Kütlesi: 39.098</p>
        <p>Grup: 1</p>
        <p>Periyot: 4</p>
        <p>Blok: s</p>
        <p>Özellikler: Potasyum, hafif bir metaldir ve reaktif bir şekilde su ile reaksiyona girer.</p>
    <a href="https://tr.wikipedia.org/wiki/Potasyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="kalsiyum-bilgi">
        <h2>Kalsiyum (Ca)</h2>
        <p>Atom Numarası: 20</p>
        <p>Atom Kütlesi: 40.078</p>
        <p>Grup: 2</p>
        <p>Periyot: 4</p>
        <p>Blok: s</p>
        <p>Özellikler: Kalsiyum, gümüşi-beyaz renkte bir metaldir ve doğal olarak sert suya tepki verir.</p>
    <a href="https://tr.wikipedia.org/wiki/Kalsiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    
    </div>
    <div class="element-bilgi" id="skandiyum-bilgi">
        <h2>Skandiyum (Sc)</h2>
        <p>Atom Numarası: 21</p>
        <p>Atom Kütlesi: 44.956</p>
        <p>Grup: 3</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Skandiyum, yumuşak, gümüşi beyaz bir metaldir ve hafif, kolayca işlenebilir ve hava ile oksitlenir.</p>
    <a href="https://tr.wikipedia.org/wiki/Skandiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="titanyum-bilgi">
        <h2>Titanyum (Ti)</h2>
        <p>Atom Numarası: 22</p>
        <p>Atom Kütlesi: 47.867</p>
        <p>Grup: 4</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Titanyum, güçlü ve hafif bir metaldir, yüksek mukavemet, düşük yoğunluk ve mükemmel korozyon direncine sahiptir.</p>
    <a href="https://tr.wikipedia.org/wiki/Titanyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="vanadyum-bilgi">
        <h2>Vanadyum (V)</h2>
        <p>Atom Numarası: 23</p>
        <p>Atom Kütlesi: 50.942</p>
        <p>Grup: 5</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Vanadyum, sert, gri renkte bir metaldir ve yüksek sıcaklıklarda çelik için bir alaşım olarak kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Vanadyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="krom-bilgi">
        <h2>Krom (Cr)</h2>
        <p>Atom Numarası: 24</p>
        <p>Atom Kütlesi: 51.996</p>
        <p>Grup: 6</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Krom, gümüş grisi bir renge sahip sert bir metaldir ve paslanmaz çelik üretiminde yaygın olarak kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Krom" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="manganez-bilgi">
        <h2>Manganez (Mn)</h2>
        <p>Atom Numarası: 25</p>
        <p>Atom Kütlesi: 54.938</p>
        <p>Grup: 7</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Manganez, gümüş renginde bir metaldir ve demir cevherlerinde bulunur.</p>
    <a href="https://tr.wikipedia.org/wiki/Manganez" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="demir-bilgi">
        <h2>Demir (Fe)</h2>
        <p>Atom Numarası: 26</p>
        <p>Atom Kütlesi: 55.845</p>
        <p>Grup: 8</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Demir, dünya kabuğunun en yaygın elementlerinden biridir ve birçok endüstriyel uygulamada kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Demir" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="kobalt-bilgi">
        <h2>Kobalt (Co)</h2>
        <p>Atom Numarası: 27</p>
        <p>Atom Kütlesi: 58.933</p>
        <p>Grup: 9</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Kobalt, sert, parlak mavimsi-beyaz bir metaldir ve manyetik özellikleri vardır.</p>
    <a href="https://tr.wikipedia.org/wiki/Kobalt" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="nikel-bilgi">
        <h2>Nikel (Ni)</h2>
        <p>Atom Numarası: 28</p>
        <p>Atom Kütlesi: 58.693</p>
        <p>Grup: 10</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Nikel, gümüşi beyaz bir renge sahip sert bir metaldir ve paslanmaz çelik üretiminde yaygın olarak kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Nikel" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="bakır-bilgi">
        <h2>Bakır (Cu)</h2>
        <p>Atom Numarası: 29</p>
        <p>Atom Kütlesi: 63.546</p>
        <p>Grup: 11</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Bakır, kızıl kahverengi bir metaldir ve iletkenlik, dövülebilirlik ve ısıyı iletme özelliklerine sahiptir.</p>
    <a href="https://tr.wikipedia.org/wiki/Bakır" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="çinko-bilgi">
        <h2>Çinko (Zn)</h2>
        <p>Atom Numarası: 30</p>
        <p>Atom Kütlesi: 65.38</p>
        <p>Grup: 12</p>
        <p>Periyot: 4</p>
        <p>Blok: d</p>
        <p>Özellikler: Çinko, mavimsi gri bir renge sahip olan ve çoğunlukla galvanizleme için kullanılan bir metaldir.</p>
    <a href="https://tr.wikipedia.org/wiki/Çinko" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="galyum-bilgi">
        <h2>Galyum (Ga)</h2>
        <p>Atom Numarası: 31</p>
        <p>Atom Kütlesi: 69.723</p>
        <p>Grup: 13</p>
        <p>Periyot: 4</p>
        <p>Blok: p</p>
        <p>Özellikler: Galyum, yumuşak, gümüş grisi bir renge sahip olan ve düşük erime noktasına sahip olan bir metaldir.</p>
    <a href="https://tr.wikipedia.org/wiki/Galyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="germanyum-bilgi">
        <h2>Germanyum (Ge)</h2>
        <p>Atom Numarası: 32</p>
        <p>Atom Kütlesi: 72.63</p>
        <p>Grup: 14</p>
        <p>Periyot: 4</p>
        <p>Blok: p</p>
        <p>Özellikler: Germanyum, metalik bir gri renge sahip olan ve yarı iletken bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Germanyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="arsenik-bilgi">
        <h2>Arsenik (As)</h2>
        <p>Atom Numarası: 33</p>
        <p>Atom Kütlesi: 74.922</p>
        <p>Grup: 15</p>
        <p>Periyot: 4</p>
        <p>Blok: p</p>
        <p>Özellikler: Arsenik, metalik grimsi-beyaz bir renge sahip olan ve zehirli olan bir yarı metaldir.</p>
    <a href="https://tr.wikipedia.org/wiki/Arsenik" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="selen-bilgi">
        <h2>Selenyum (Se)</h2>
        <p>Atom Numarası: 34</p>
        <p>Atom Kütlesi: 78.971</p>
        <p>Grup: 16</p>
        <p>Periyot: 4</p>
        <p>Blok: p</p>
        <p>Özellikler: Selenyum, kırılgan, kırmızımsı bir gri renkte olan ve fotoelektrik etkide kullanılan bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Selen" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="brom-bilgi">
        <h2>Brom (Br)</h2>
        <p>Atom Numarası: 35</p>
        <p>Atom Kütlesi: 79.904</p>
        <p>Grup: 17</p>
        <p>Periyot: 4</p>
        <p>Blok: p</p>
        <p>Özellikler: Brom, koyu kırmızımsı-kahverengi bir sıvıdır ve birçok endüstriyel uygulamada kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Brom" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="kripton-bilgi">
        <h2>Kripton (Kr)</h2>
        <p>Atom Numarası: 36</p>
        <p>Atom Kütlesi: 83.798</p>
        <p>Grup: 18</p>
        <p>Periyot: 4</p>
        <p>Blok: p</p>
        <p>Özellikler: Kripton, renksiz, kokusuz, tatsız bir gazdır ve lamba ampullerinde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Kripton" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="rubidyum-bilgi">
        <h2>Rubidyum (Rb)</h2>
        <p>Atom Numarası: 37</p>
        <p>Atom Kütlesi: 85.468</p>
        <p>Grup: 1</p>
        <p>Periyot: 5</p>
        <p>Blok: s</p>
        <p>Özellikler: Rubidyum, parlak beyaz renkli ve yarı metalik bir özelliğe sahip bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Rubidyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="stronsiyum-bilgi">
        <h2>Stronsiyum (Sr)</h2>
        <p>Atom Numarası: 38</p>
        <p>Atom Kütlesi: 87.62</p>
        <p>Grup: 2</p>
        <p>Periyot: 5</p>
        <p>Blok: s</p>
        <p>Özellikler: Stronsiyum, yumuşak sarımsı gri renkte olan ve çeşitli endüstriyel uygulamalarda kullanılan bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Stronsiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="itriyum-bilgi">
        <h2>Itriyum (Y)</h2>
        <p>Atom Numarası: 39</p>
        <p>Atom Kütlesi: 88.906</p>
        <p>Grup: 3</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: İtriyum, gümüşi beyaz renkte bir metaldir ve optik teknolojide, manyetik alanlarda ve çelik alaşımlarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Itriyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="zirkonyum-bilgi">
        <h2>Zirkonyum (Zr)</h2>
        <p>Atom Numarası: 40</p>
        <p>Atom Kütlesi: 91.224</p>
        <p>Grup: 4</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Zirkonyum, gümüşi beyaz bir metaldir ve yüksek sıcaklık dayanımına ve korozyon direncine sahiptir.</p>
    <a href="https://tr.wikipedia.org/wiki/Zirkonyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="niobyum-bilgi">
        <h2>Niobyum (Nb)</h2>
        <p>Atom Numarası: 41</p>
        <p>Atom Kütlesi: 92.906</p>
        <p>Grup: 5</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Niobyum, yumuşak, dövülebilir ve çekilebilir bir metaldir ve yüksek sıcaklık ve basınca dayanıklıdır.</p>
    <a href="https://tr.wikipedia.org/wiki/Niobyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="molybden-bilgi">
        <h2>Molibden (Mo)</h2>
        <p>Atom Numarası: 42</p>
        <p>Atom Kütlesi: 95.95</p>
        <p>Grup: 6</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Molibden, yüksek ergime noktasına ve yüksek mukavemetli alaşımlar oluşturma yeteneğine sahip bir metaldir.</p>
    <a href="https://tr.wikipedia.org/wiki/Molybden" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="teknetiyum-bilgi">
        <h2>Teknetiyum (Tc)</h2>
        <p>Atom Numarası: 43</p>
        <p>Atom Kütlesi: [97]</p>
        <p>Grup: 7</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Teknetiyum, kararsız ve radyoaktif bir elementtir ve laboratuvarlarda üretilebilen ender radyoaktif elementlerden biridir.</p>
    <a href="https://tr.wikipedia.org/wiki/Teknetiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="rutenyum-bilgi">
        <h2>Rutenyum (Ru)</h2>
        <p>Atom Numarası: 44</p>
        <p>Atom Kütlesi: 101.07</p>
        <p>Grup: 8</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Rutenyum, platinden daha sert olan ve çeşitli kimyasal endüstrilerde katalizör olarak kullanılan bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Rutenyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="rhodium-bilgi">
        <h2>Rodyum (Rh)</h2>
        <p>Atom Numarası: 45</p>
        <p>Atom Kütlesi: 102.91</p>
        <p>Grup: 9</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Rodyum, parlak beyaz bir metaldir ve endüstriyel katalizörlerin yanı sıra mücevherlerde de kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Rhodium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="paladyum-bilgi">
        <h2>Paladyum (Pd)</h2>
        <p>Atom Numarası: 46</p>
        <p>Atom Kütlesi: 106.42</p>
        <p>Grup: 10</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Paladyum, platin ve altından daha pahalı olan ve endüstride katalizörlerde, elektrik kontaklarında ve mücevherlerde kullanılan bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Paladyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="gümüş-bilgi">
        <h2>Gümüş (Ag)</h2>
        <p>Atom Numarası: 47</p>
        <p>Atom Kütlesi: 107.87</p>
        <p>Grup: 11</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Gümüş, parlak beyaz bir metaldir ve elektrik iletkenliği, ısı iletkenliği ve optik refleksiyon özellikleri nedeniyle yaygın olarak kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Gumus" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="kadmiyum-bilgi">
        <h2>Kadmiyum (Cd)</h2>
        <p>Atom Numarası: 48</p>
        <p>Atom Kütlesi: 112.41</p>
        <p>Grup: 12</p>
        <p>Periyot: 5</p>
        <p>Blok: d</p>
        <p>Özellikler: Kadmiyum, yumuşak, dövülebilir ve çekilebilir bir metaldir ve bazı pil ve yarı iletken uygulamalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Kadmiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="indiyum-bilgi">
        <h2>İndiyum (In)</h2>
        <p>Atom Numarası: 49</p>
        <p>Atom Kütlesi: 114.82</p>
        <p>Grup: 13</p>
        <p>Periyot: 5</p>
        <p>Blok: p</p>
        <p>Özellikler: İndiyum, yumuşak, dövülebilir ve erime noktası düşük olan bir metaldir ve bazı elektronik cihazlarda ve düşük erime noktalı alaşımlarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Indiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="kalay-bilgi">
        <h2>Kalay (Sn)</h2>
        <p>Atom Numarası: 50</p>
        <p>Atom Kütlesi: 118.71</p>
        <p>Grup: 14</p>
        <p>Periyot: 5</p>
        <p>Blok: p</p>
        <p>Özellikler: Kalay, yumuşak, parlak ve gri renkli bir metaldir ve genellikle kaplama olarak kullanılır veya alaşımların bir bileşeni olarak bulunur.</p>
    <a href="https://tr.wikipedia.org/wiki/Kalay" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="antimon-bilgi">
        <h2>Antimon (Sb)</h2>
        <p>Atom Numarası: 51</p>
        <p>Atom Kütlesi: 121.76</p>
        <p>Grup: 15</p>
        <p>Periyot: 5</p>
        <p>Blok: p</p>
        <p>Özellikler: Antimon, çeşitli endüstriyel uygulamalarda kullanılan parlak beyaz bir metaloiddir ve bazı bileşiklerinde toksik olabilir.</p>
    <a href="https://tr.wikipedia.org/wiki/Antimon" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="tellur-bilgi">
        <h2>Tellur (Te)</h2>
        <p>Atom Numarası: 52</p>
        <p>Atom Kütlesi: 127.6</p>
        <p>Grup: 16</p>
        <p>Periyot: 5</p>
        <p>Blok: p</p>
        <p>Özellikler: Tellur, kırılgan, metalik bir görünümü olan ve bazı bileşiklerinde yarı iletkenlik gösteren bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Tellur" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="iyot-bilgi">
        <h2>İyot (I)</h2>
        <p>Atom Numarası: 53</p>
        <p>Atom Kütlesi: 126.9</p>
        <p>Grup: 17</p>
        <p>Periyot: 5</p>
        <p>Blok: p</p>
        <p>Özellikler: İyot, koyu mor kristaller oluşturan ve tıbbi antiseptiklerde ve bazı endüstriyel uygulamalarda kullanılan bir halojendir.</p>
    <a href="https://tr.wikipedia.org/wiki/Iyot" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="ksenon-bilgi">
        <h2>Ksenon (Xe)</h2>
        <p>Atom Numarası: 54</p>
        <p>Atom Kütlesi: 131.29</p>
        <p>Grup: 18</p>
        <p>Periyot: 5</p>
        <p>Blok: p</p>
        <p>Özellikler: Ksenon, renksiz, kokusuz ve aşırı derecede reaktif olmayan bir asal gazdır ve bazı aydınlatma ve tıbbi uygulamalarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Ksenon" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="sezyum-bilgi">
        <h2>Sezyum (Cs)</h2>
        <p>Atom Numarası: 55</p>
        <p>Atom Kütlesi: 132.91</p>
        <p>Grup: 1</p>
        <p>Periyot: 6</p>
        <p>Blok: s</p>
        <p>Özellikler: Sezyum, yumuşak, altın rengi bir alkali metaldir ve atomik saati, fotoelektrik hücreleri ve vakum tüplerinde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Sezyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="baryum-bilgi">
        <h2>Baryum (Ba)</h2>
        <p>Atom Numarası: 56</p>
        <p>Atom Kütlesi: 137.33</p>
        <p>Grup: 2</p>
        <p>Periyot: 6</p>
        <p>Blok: s</p>
        <p>Özellikler: Baryum, parlak bir gümüş gri metaldir ve televizyon tüpleri, gaz deşarj lambaları ve yeşil ateşte pirotekniklerde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Baryum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="lantan-bilgi">
        <h2>Lantan (La)</h2>
        <p>Atom Numarası: 57</p>
        <p>Atom Kütlesi: 138.91</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Lantan, lantanit serisinin ilk elementidir ve çeşitli endüstriyel uygulamalarda ve bazı tıbbi cihazlarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Lantan" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="serum-bilgi">
        <h2>Serum (Ce)</h2>
        <p>Atom Numarası: 58</p>
        <p>Atom Kütlesi: 140.12</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Serum, lantanit serisinin ikinci elementidir ve lamba filamanları, manyetik malzemeler ve katalizörlerde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Serum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="praseodim-bilgi">
        <h2>Praseodim (Pr)</h2>
        <p>Atom Numarası: 59</p>
        <p>Atom Kütlesi: 140.91</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Praseodim, lantanit serisinin üçüncü elementidir ve bazı alaşımlarda ve lamba filamanlarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Praseodim" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="neodim-bilgi">
        <h2>Neodim (Nd)</h2>
        <p>Atom Numarası: 60</p>
        <p>Atom Kütlesi: 144.24</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Neodim, güçlü mıknatıslar oluşturmak için kullanılan nadir bir toprak elementidir ve lazerler, manyetik malzemeler ve bazı tıbbi cihazlarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Neodim" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="prometyum-bilgi">
        <h2>Prometyum (Pm)</h2>
        <p>Atom Numarası: 61</p>
        <p>Atom Kütlesi: [145]</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Prometyum, kararsız ve radyoaktif bir elementtir ve bazı tıbbi cihazlarda ve endüstriyel ölçüm cihazlarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Prometyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="samaryum-bilgi">
        <h2>Samaryum (Sm)</h2>
        <p>Atom Numarası: 62</p>
        <p>Atom Kütlesi: 150.36</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Samaryum, nadir toprak elementlerinden biridir ve manyetik alaşımlarda, lamba filamanlarında ve lazerlerde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Samaryum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    
    <div class="element-bilgi" id="europiyum-bilgi">
        <h2>Europiyum (Eu)</h2>
        <p>Atom Numarası: 63</p>
        <p>Atom Kütlesi: 151.96</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Europiyum, kırmızı bir fosforesans üreten nadir bir toprak elementidir ve televizyon ekranlarında ve lazerlerde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Europiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    
    <div class="element-bilgi" id="gadolinium-bilgi">
        <h2>Gadolinyum (Gd)</h2>
        <p>Atom Numarası: 64</p>
        <p>Atom Kütlesi: 157.25</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Gadolinyum, manyetik rezonans görüntülemede (MRG) kullanılan kontrast maddelerinin bir bileşeni olarak kullanılan bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Gadolinium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="terbiyum-bilgi">
        <h2>Terbiyum (Tb)</h2>
        <p>Atom Numarası: 65</p>
        <p>Atom Kütlesi: 158.93</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Terbiyum, yüksek mıknatıslık ve manyetik malzemelerde kullanılan nadir bir toprak elementidir.</p>
    <a href="https://tr.wikipedia.org/wiki/Terbiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="disprosiyum-bilgi">
        <h2>Disprosiyum (Dy)</h2>
        <p>Atom Numarası: 66</p>
        <p>Atom Kütlesi: 162.50</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Disprosiyum, manyetik alaşımlar ve lazerlerde kullanılan nadir bir toprak elementidir.</p>
    <a href="https://tr.wikipedia.org/wiki/Disprosiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="holmium-bilgi">
        <h2>Holmiyum (Ho)</h2>
        <p>Atom Numarası: 67</p>
        <p>Atom Kütlesi: 164.93</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Holmiyum, manyetik uygulamalarda ve optik cihazlarda kullanılan nadir bir toprak elementidir.</p>
    <a href="https://tr.wikipedia.org/wiki/Holmium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="erbiyum-bilgi">
        <h2>Erbiyum (Er)</h2>
        <p>Atom Numarası: 68</p>
        <p>Atom Kütlesi: 167.26</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Erbiyum, manyetik malzemelerde ve lazerlerde kullanılan nadir bir toprak elementidir.</p>
    <a href="https://tr.wikipedia.org/wiki/Erbiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="tulyum-bilgi">
        <h2>Tulyum (Tm)</h2>
        <p>Atom Numarası: 69</p>
       <p>Atom Kütlesi: 168.93</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Tulyum, lazerlerde, manyetik cihazlarda ve optik fiberlerde kullanılan nadir bir toprak elementidir.</p>
    <a href="https://tr.wikipedia.org/wiki/Tulyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="iterbiyum-bilgi">
        <h2>İterbiyum (Yb)</h2>
        <p>Atom Numarası: 70</p>
        <p>Atom Kütlesi: 173.05</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: İterbiyum, optik fiber iletişiminde, lazerlerde ve manyetik cihazlarda kullanılan nadir bir toprak elementidir.</p>
    <a href="https://tr.wikipedia.org/wiki/İterbiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="lutesyum-bilgi">
        <h2>Lutesyum (Lu)</h2>
        <p>Atom Numarası: 71</p>
        <p>Atom Kütlesi: 174.97</p>
        <p>Grup: Lantanitler</p>
        <p>Periyot: 6</p>
        <p>Blok: f</p>
        <p>Özellikler: Lutesyum, nadir toprak elementleri grubunun son elementidir ve lazerlerde, manyetik malzemelerde ve katalizörlerde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Lutesyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="hafniyum-bilgi">
        <h2>Hafniyum (Hf)</h2>
        <p>Atom Numarası: 72</p>
        <p>Atom Kütlesi: 178.49</p>
        <p>Grup: 4</p>
        <p>Periyot: 6</p>
        <p>Blok: d</p>
        <p>Özellikler: Hafniyum, yüksek erime noktası ve oksidasyon direnci nedeniyle nükleer reaktörlerde, uçak motorlarında ve hassas cihazlarda kullanılan bir metaldir.</p>
    <a href="https://tr.wikipedia.org/wiki/Hafniyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="tantal-bilgi">
        <h2>Tantal (Ta)</h2>
        <p>Atom Numarası: 73</p>
        <p>Atom Kütlesi: 180.95</p>
        <p>Grup: 5</p>
        <p>Periyot: 6</p>
        <p>Blok: d</p>
        <p>Özellikler: Tantal, yüksek sıcaklıkta ve korozyona dayanıklı olması nedeniyle kimya endüstrisinde, elektronik cihazlarda ve cerrahi implantlarda kullanılan bir metaldir.</p>
    <a href="https://tr.wikipedia.org/wiki/Tantal" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="tungsten-bilgi">
        <h2>Tungsten (W)</h2>
        <p>Atom Numarası: 74</p>
        <p>Atom Kütlesi: 183.84</p>
        <p>Grup: 6</p>
        <p>Periyot: 6</p>
        <p>Blok: d</p>
        <p>Özellikler: Tungsten, en yüksek erime noktasına sahip metaldir ve ampullerde, x-ışını tüplerinde ve yüksek mukavemetli alaşımlarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Tungsten" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="rhenium-bilgi">
        <h2>Renyum (Re)</h2>
        <p>Atom Numarası: 75</p>
        <p>Atom Kütlesi: 186.21</p>
        <p>Grup: 7</p>
        <p>Periyot: 6</p>
        <p>Blok: d</p>
        <p>Özellikler: Renyum, en yüksek erime noktasına sahip olan nadir bulunan bir metaldir ve yüksek sıcaklık ve basınç uygulamalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Rhenium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="osmium-bilgi">
        <h2>Osmiyum (Os)</h2>
        <p>Atom Numarası: 76</p>
        <p>Atom Kütlesi: 190.23</p>
        <p>Grup: 8</p>
        <p>Periyot: 6</p>
        <p>Blok: d</p>
        <p>Özellikler: Osmiyum, yoğunluğu en yüksek olan elementlerden biridir ve bazı endüstriyel süreçlerde katalizör olarak kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Osmium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="iridyum-bilgi">
        <h2>İridyum (Ir)</h2>
        <p>Atom Numarası: 77</p>
        <p>Atom Kütlesi: 192.22</p>
        <p>Grup: 9</p>
        <p>Periyot: 6</p>
        <p>Blok: d</p>
        <p>Özellikler: İridyum, platinden daha sert olan ve endüstriyel uygulamalarda, özellikle yüksek sıcaklık ve basınç koşullarında kullanılan bir metaldir.</p>
    <a href="https://tr.wikipedia.org/wiki/Iridyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="platina-bilgi">
        <h2>Platina (Pt)</h2>
        <p>Atom Numarası: 78</p>
        <p>Atom Kütlesi: 195.08</p>
        <p>Grup: 10</p>
        <p>Periyot: 6</p>
        <p>Blok: d</p>
        <p>Özellikler: Platina, değerli bir metal olup, mücevher yapımında, katalizörlerde ve diş amalgamlarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Platina" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="altin-bilgi">
        <h2>Altın (Au)</h2>
    <p>Atom Numarası: 79</p>
    <p>Atom Kütlesi: 196.97</p>
    <p>Grup: 11</p>
    <p>Periyot: 6</p>
    <p>Blok: d</p>
    <p>Özellikler: Altın, parlak sarı bir metal olup, mücevher yapımında, elektronik cihazlarda ve tıbbi uygulamalarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Altin" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="civa-bilgi">
        <h2>Cıva (Hg)</h2>
        <p>Atom Numarası: 80</p>
        <p>Atom Kütlesi: 200.59</p>
        <p>Grup: 12</p>
        <p>Periyot: 6</p>
        <p>Blok: d</p>
        <p>Özellikler: Cıva, oda sıcaklığında sıvı halde bulunan tek metaldir ve termometrelerde, barometrelerde ve elektrikli cihazlarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Altin" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="talyum-bilgi">
        <h2>Talyum (Tl)</h2>
        <p>Atom Numarası: 81</p>
        <p>Atom Kütlesi: 204.38</p>
        <p>Grup: 13</p>
        <p>Periyot: 6</p>
        <p>Blok: p</p>
        <p>Özellikler: Talyum, yumuşak, toksik bir metaldir ve bazı elektronik bileşenlerde ve tıbbi cihazlarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Talyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="kurşun-bilgi">
        <h2>Kurşun (Pb)</h2>
        <p>Atom Numarası: 82</p>
        <p>Atom Kütlesi: 207.2</p>
        <p>Grup: 14</p>
        <p>Periyot: 6</p>
        <p>Blok: p</p>
        <p>Özellikler: Kurşun, yumuşak, dövülebilir ve çekilebilir bir metaldir ve akülerde, kurşun kalemlerde ve yapım malzemelerinde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Kursun" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="bismut-bilgi">
        <h2>Bismut (Bi)</h2>
        <p>Atom Numarası: 83</p>
        <p>Atom Kütlesi: 208.98</p>
        <p>Grup: 15</p>
        <p>Periyot: 6</p>
        <p>Blok: p</p>
        <p>Özellikler: Bismut, kırılgan bir metaldir ve bazı tıbbi cihazlarda, yangın söndürücülerde ve lehimleme malzemelerinde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Bismut" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="polonyum-bilgi">
        <h2>Polonyum (Po)</h2>
        <p>Atom Numarası: 84</p>
        <p>Atom Kütlesi: [209]</p>
        <p>Grup: 16</p>
        <p>Periyot: 6</p>
        <p>Blok: p</p>
        <p>Özellikler: Polonyum, çok nadir bulunan ve yüksek derecede radyoaktif olan bir elementtir ve bazı nükleer güç sistemlerinde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Polonyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="astat-bilgi">
        <h2>Astatin (At)</h2>
        <p>Atom Numarası: 85</p>
        <p>Atom Kütlesi: [210]</p>
        <p>Grup: 17</p>
        <p>Periyot: 6</p>
        <p>Blok: p</p>
        <p>Özellikler: Astatin, kararsız ve radyoaktif bir elementtir ve doğada çok nadir bulunur.</p>
    <a href="https://tr.wikipedia.org/wiki/Astat" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="radon-bilgi">
        <h2>Radon (Rn)</h2>
        <p>Atom Numarası: 86</p>
        <p>Atom Kütlesi: [222]</p>
        <p>Grup: 18</p>
        <p>Periyot: 6</p>
        <p>Blok: p</p>
        <p>Özellikler: Radon, renksiz, kokusuz ve radyoaktif bir gazdır ve bazı yeraltı madenlerinde doğal olarak bulunabilir.</p>
    <a href="https://tr.wikipedia.org/wiki/Radon" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="fransiyum-bilgi">
        <h2>Fransiyum (Fr)</h2>
        <p>Atom Numarası: 87</p>
        <p>Atom Kütlesi: [223]</p>
        <p>Grup: 1</p>
        <p>Periyot: 7</p>
        <p>Blok: s</p>
        <p>Özellikler: Fransiyum, kararsız ve radyoaktif bir elementtir ve doğada çok nadir bulunur.</p>
    <a href="https://tr.wikipedia.org/wiki/Fransiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="radyum-bilgi">
        <h2>Radyum (Ra)</h2>
        <p>Atom Numarası: 88</p>
        <p>Atom Kütlesi: [226]</p>
        <p>Grup: 2</p>
        <p>Periyot: 7</p>
        <p>Blok: s</p>
        <p>Özellikler: Radyum, kararsız ve radyoaktif bir elementtir ve doğada uranyum ve toriumun bozunması sonucu oluşabilir.</p>
    <a href="https://tr.wikipedia.org/wiki/Radyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="aktinyum-bilgi">
        <h2>Aktinyum (Ac)</h2>
        <p>Atom Numarası: 89</p>
        <p>Atom Kütlesi: [227]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
    <p>Blok: f</p>
        <p>Özellikler: Aktinyum, kararsız ve radyoaktif bir elementtir ve bazı nükleer reaktörlerde ve radyoaktif izotop üretiminde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Aktinyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="toriyum-bilgi">
        <h2>Toryum (Th)</h2>
        <p>Atom Numarası: 90</p>
        <p>Atom Kütlesi: 232.04</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Toryum, nadir bulunan ancak çeşitli endüstriyel ve bilimsel uygulamalarda kullanılan bir aktinit elementidir.</p>
    <a href="https://tr.wikipedia.org/wiki/Toryum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="protaktinyum-bilgi">
        <h2>Protaktinyum (Pa)</h2>
        <p>Atom Numarası: 91</p>
        <p>Atom Kütlesi: [231]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Protaktinyum, kararsız ve radyoaktif bir elementtir ve bazı nükleer reaktörlerde ve bilimsel araştırmalarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Protaktinyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="uranyum-bilgi">
        <h2>Uranyum (U)</h2>
        <p>Atom Numarası: 92</p>
        <p>Atom Kütlesi: 238.03</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Uranyum, uranyum serisinin ilk elementidir ve nükleer enerji üretimi ve nükleer silah üretimi gibi alanlarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Uranyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="neptinyum-bilgi">
        <h2>Neptinyum (Np)</h2>
        <p>Atom Numarası: 93</p>
        <p>Atom Kütlesi: [237]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Neptinyum, kararsız ve radyoaktif bir elementtir ve nükleer reaktörlerde ve nükleer silah üretiminde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Neptinyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="plutonyum-bilgi">
        <h2>Plütonyum (Pu)</h2>
        <p>Atom Numarası: 94</p>
        <p>Atom Kütlesi: [244]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Plütonyum, yapay olarak üretilen ve nükleer enerji üretimi ve nükleer silah üretimi gibi alanlarda kullanılan bir elementtir.</p>
    <a href="https://tr.wikipedia.org/wiki/Plutonyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="amerikyum-bilgi">
        <h2>Amerikyum (Am)</h2>
        <p>Atom Numarası: 95</p>
        <p>Atom Kütlesi: [243]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Amerikyum, kararsız ve radyoaktif bir elementtir ve bazı endüstriyel ve tıbbi uygulamalarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Amerikyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="küriyum-bilgi">
        <h2>Küriyum (Cm)</h2>
        <p>Atom Numarası: 96</p>
        <p>Atom Kütlesi: [247]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Küriyum, kararsız ve radyoaktif bir elementtir ve nükleer reaktörlerde ve nükleer silah üretiminde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Kuriyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="berkelium-bilgi">
        <h2>Berkelyum (Bk)</h2>
        <p>Atom Numarası: 97</p>
        <p>Atom Kütlesi: [247]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Berkelyum, kararsız ve radyoaktif bir elementtir ve bilimsel araştırmalarda ve nükleer reaktörlerde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Berkelium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="kaliforniyum-bilgi">
        <h2>Kaliforniyum (Cf)</h2>
        <p>Atom Numarası: 98</p>
        <p>Atom Kütlesi: [251]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Kaliforniyum, kararsız ve radyoaktif bir elementtir ve nükleer reaktörlerde ve bilimsel araştırmalarda kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Kaliforniyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="einsteinium-bilgi">
        <h2>Einştaynyum (Es)</h2>
        <p>Atom Numarası: 99</p>
        <p>Atom Kütlesi: [252]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Einsteinium, kararsız ve radyoaktif bir elementtir ve bilimsel araştırmalarda ve nükleer reaktörlerde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Einsteinium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="fermium-bilgi">
        <h2>Fermiyum (Fm)</h2>
        <p>Atom Numarası: 100</p>
        <p>Atom Kütlesi: [257]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Fermiyum, kararsız ve radyoaktif bir elementtir ve bilimsel araştırmalarda ve nükleer reaktörlerde kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Fermium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="mendeleviyum-bilgi">
        <h2>Mendeleviyum (Md)</h2>
        <p>Atom Numarası: 101</p>
        <p>Atom Kütlesi: [258]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Mendeleviyum, kararsız ve radyoaktif bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Mendeleviyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="nobelyum-bilgi">
        <h2>Nobelyum (No)</h2>
        <p>Atom Numarası: 102</p>
        <p>Atom Kütlesi: [259]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Nobelyum, kararsız ve radyoaktif bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Nobelyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="lawrensiyum-bilgi">
        <h2>Lawrensiyum (Lr)</h2>
        <p>Atom Numarası: 103</p>
        <p>Atom Kütlesi: [262]</p>
        <p>Grup: Aktinitler</p>
        <p>Periyot: 7</p>
        <p>Blok: f</p>
        <p>Özellikler: Lawrensiyum, kararsız ve radyoaktif bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Lawrensiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="rutherfordiyum-bilgi">
        <h2>Rutherfordiyum (Rf)</h2>
        <p>Atom Numarası: 104</p>
        <p>Atom Kütlesi: [267]</p>
        <p>Grup: 4</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Rutherfordiyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Rutherfordiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="dubniyum-bilgi">
        <h2>Dubniyum (Db)</h2>
        <p>Atom Numarası: 105</p>
        <p>Atom Kütlesi: [268]</p>
        <p>Grup: 5</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Dubniyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Dubniyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="seaborgiyum-bilgi">
        <h2>Seaborgiyum (Sg)</h2>
        <p>Atom Numarası: 106</p>
        <p>Atom Kütlesi: [269]</p>
        <p>Grup: 6</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Seaborgiyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Seaborgiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="bohriyum-bilgi">
        <h2>Bohriyum (Bh)</h2>
        <p>Atom Numarası: 107</p>
        <p>Atom Kütlesi: [270]</p>
        <p>Grup: 7</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Bohriyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Bohriyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="hassium-bilgi">
        <h2>Hassium (Hs)</h2>
        <p>Atom Numarası: 108</p>
        <p>Atom Kütlesi: [277]</p>
        <p>Grup: 8</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Hassium, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Hassium" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="meitneriyum-bilgi">
        <h2>Meitneriyum (Mt)</h2>
        <p>Atom Numarası: 109</p>
        <p>Atom Kütlesi: [278]</p>
        <p>Grup: 9</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Meitneriyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Meitneriyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="darmstadtiyum-bilgi">
        <h2>Darmstadtium (Ds)</h2>
        <p>Atom Numarası: 110</p>
        <p>Atom Kütlesi: [281]</p>
        <p>Grup: 10</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Darmstadtium, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Darmstadtiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="roentgeniyum-bilgi">
        <h2>Roentgeniyum (Rg)</h2>
        <p>Atom Numarası: 111</p>
        <p>Atom Kütlesi: [282]</p>
        <p>Grup: 11</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Roentgeniyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Roentgeniyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="kopernikyum-bilgi">
        <h2>Kopernikyum (Cn)</h2>
        <p>Atom Numarası: 112</p>
        <p>Atom Kütlesi: [285]</p>
        <p>Grup: 12</p>
        <p>Periyot: 7</p>
        <p>Blok: d</p>
        <p>Özellikler: Kopernikyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Kopernikyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="nihonyum-bilgi">
        <h2>Nihonyum (Nh)</h2>
        <p>Atom Numarası: 113</p>
        <p>Atom Kütlesi: [286]</p>
        <p>Grup: 13</p>
        <p>Periyot: 7</p>
        <p>Blok: p</p>
        <p>Özellikler: Nihonyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Nihonyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="fleroviyum-bilgi">
        <h2>Fleroviyum (Fl)</h2>
        <p>Atom Numarası: 114</p>
        <p>Atom Kütlesi: [289]</p>
        <p>Grup:14</p>
        <p>Periyot: 7</p>
        <p>Blok: p</p>
        <p>Özellikler: Fleroviyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Fleroviyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="moskoviyum-bilgi">
        <h2>Moskoviyum (Mc)</h2>
        <p>Atom Numarası: 115</p>
        <p>Atom Kütlesi: [290]</p>
        <p>Grup: 15</p>
        <p>Periyot: 7</p>
        <p>Blok: p</p>
        <p>Özellikler: Moskoviyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Moskoviyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="livermoryum-bilgi">
        <h2>Livermoryum (Lv)</h2>
        <p>Atom Numarası: 116</p>
        <p>Atom Kütlesi: [293]</p>
        <p>Grup: 16</p>
        <p>Periyot: 7</p>
        <p>Blok: p</p>
        <p>Özellikler: Livermoryum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Livermoryum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="tenessiyum-bilgi">
        <h2>Tenessiyum (Ts)</h2>
        <p>Atom Numarası: 117</p>
        <p>Atom Kütlesi: [294]</p>
        <p>Grup: 17</p>
        <p>Periyot: 7</p>
        <p>Blok: p</p>
        <p>Özellikler: Tenessiyum, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Tenessiyum" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    <div class="element-bilgi" id="oganesson-bilgi">
        <h2>Oganesson (Og)</h2>
        <p>Atom Numarası: 118</p>
        <p>Atom Kütlesi: [294]</p>
        <p>Grup: 18</p>
        <p>Periyot: 7</p>
        <p>Blok: p</p>
        <p>Özellikler: Oganesson, kararsız ve yapay olarak üretilmiş bir elementtir ve laboratuvar araştırmalarında kullanılır.</p>
    <a href="https://tr.wikipedia.org/wiki/Oganesson" class="daha-fazlasi-icin-tiklayin">Daha fazlası için tıklayın</a>
    </div>
    </div>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            var elements = document.querySelectorAll(".element");
            var bilgiler = document.querySelectorAll(".element-bilgi");

            elements.forEach(function(element) {
                element.addEventListener("click", function() {
                    var elementId = element.id.replace('m-', '');
                    var bilgiElement = document.getElementById(elementId + "-bilgi");
                    
                    // Bilgi elementinin aktiflik durumunu kontrol edin
                    if (bilgiElement.classList.contains("active")) {
                        bilgiElement.classList.remove("active");
                        bilgiElement.style.display = "none";
                    } else {
                        bilgiler.forEach(function(bilgi) {
                            bilgi.classList.remove("active");
                            bilgi.style.display = "none";
                        });
                        bilgiElement.classList.add("active");
                        bilgiElement.style.display = "block";
                        
                        // Mobilde tıklanan elementin hemen altına bilgiyi ekleyin
                        if (window.innerWidth <= 600) {
                            element.insertAdjacentElement('afterend', bilgiElement);
                        } else {
                            document.getElementById("element-info").appendChild(bilgiElement);
                        }
                    }
                });
            });
        });
    </script>
</body>
</html>
