<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Nadyezhda SL One](#nadyezhda-sl-one)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->






# Nadyezhda SL One

**Forked from http://www.twardoch.com/fonts/**

Contained herin is the Nadyezhda SL One font
in OpenType TT (.ttf) format.

Extensions copyright (c) 2007 by Silesian Letters.
Original copyright for Bitstream Vera Mono:
(c) 2003 by Bitstream, Inc. All Rights Reserved.

Please consult COPYRIGHT.TXT for license and copyright details.

This font is a special version of the Bitstream Vera Mono font,
originally designed by Jim Lyles. This version has been extended
by Adam Twardoch, Silesian Letters (http://www.silesian.com ).

This font is intended for testing of OpenType Layout features support
in an application. Using a special test string (see below), the user
can selectively turn on and off OpenType features in the application's
UI and observe which OpenType feature tags are being applied to the
text. Each feature includes one lookup that substitutes two particular
Latin lowercase letters with a special glyph that shows the feature
tag associated with that feature. All lookups are GSUB LookupType 4
(ligature) lookups and are registered in the Latin (latn) default
languagesystem.

The font implements all OpenType feature tags registered in the
OpenType specification version 1.4, as well as two unregistered
tags: "ss21" and "ss22".

Note that many OpenType Layout features should not be implemented
this way in real-world fonts. For example, the "nukt" (Nukta form)
feature only makes sense when registered in an Indic script, not in
the Latin script. Many of these features should be applied
automatically in certain language/script contexts by the OpenType
Layout engine, and this font is not suitable for testing such
behavior. Also, the recommended implementation for many features
is to include positioning lookups rather than substitution lookups,
and this font also does not fulfil these expectations.

Nonetheless, the font is useful for testing issues such as:
* What feature tags does my application apply by default, without
any user interaction?
* When triggering a particular UI item for applying a certain feature,
is the expected feature being actually applied?
* Does my application have human-readable UI labels for all possible
OpenType features?
* Are the human-readable UI labels for OpenType features localized
into other languages in a sensible way?

"Nadyezhda" is Russian for "Hope". Along with "Vera" (which was also
the original name for this typeface, and is Russian for "Faith") and
with "Lyubov" ("Love"), they form the three Biblical virtues,
and rank among the most popular Russian female given names.

The special test string is:

aa ab ac ad ae af ag ah ai aj ak al am
an ao ap aq ar as at au av aw ax ay az
ba bb bc bd be bf bg bh bi bj bk bl bm
bn bo bp bq br bs bt bu bv bw bx by bz
ca cb cc cd ce cf cg ch ci cj ck cl cm
cn co cp cq cr cs ct cu cv cw cx cy cz
da db dc dd de df dg dh di dj dk dl dm
dn do dp dq dr ds dt du dv dw dx dy dz
ea eb ec ed ee ef eg eh ei ej ek el em
en eo ep eq er es et eu ev ew ex ey ez

The following is the Adobe AFDKO source code for the features
defined in the font:

feature aalt { feature abvf; feature abvm; feature abvs; feature afrc; feature akhn; feature blwf; feature blwm; feature blws; feature c2pc; feature c2sc; feature calt; feature case; feature ccmp; feature clig; feature cjct; feature cpsp; feature cswh; feature curs; feature dflt; feature dist; feature dlig; feature dnom; feature expt; feature falt; feature fin2; feature fin3; feature fina; feature frac; feature fwid; feature half; feature haln; feature halt; feature hist; feature hkna; feature hlig; feature hngl; feature hojo; feature hwid; feature init; feature isol; feature ital; feature jalt; feature jp78; feature jp83; feature jp90; feature jp04; feature kern; feature lfbd; feature liga; feature ljmo; feature lnum; feature locl; feature mark; feature med2; feature medi; feature mgrk; feature mkmk; feature mset; feature nalt; feature nlck; feature nukt; feature numr; feature onum; feature opbd; feature ordn; feature ornm; feature palt; feature pcap; feature pnum; feature pref; feature pres; feature pstf; feature psts; feature pwid; feature qwid; feature rand; feature rkrf; feature rlig; feature rphf; feature rtbd; feature rtla; feature ruby; feature salt; feature sinf; feature size; feature smcp; feature smpl; feature ss01; feature ss02; feature ss03; feature ss04; feature ss05; feature ss06; feature ss07; feature ss08; feature ss09; feature ss10; feature ss11; feature ss12; feature ss13; feature ss14; feature ss15; feature ss16; feature ss17; feature ss18; feature ss19; feature ss20; feature ss21; feature ss22; feature subs; feature sups; feature swsh; feature titl; feature tjmo; feature tnam; feature tnum; feature trad; feature twid; feature unic; feature valt; feature vatu; feature vert; feature vhal; feature vjmo; feature vkna; feature vkrn; feature vpal; feature vrt2; feature zero; } aalt;
feature abvf { sub a b by a_b_v_f; } abvf;
feature abvm { sub a c by a_b_v_m; } abvm;
feature abvs { sub a d by a_b_v_s; } abvs;
feature afrc { sub a e by a_f_r_c; } afrc;
feature akhn { sub a f by a_k_h_n; } akhn;
feature blwf { sub a g by b_l_w_f; } blwf;
feature blwm { sub a h by b_l_w_m; } blwm;
feature blws { sub a i by b_l_w_s; } blws;
feature c2pc { sub a j by c_two_p_c; } c2pc;
feature c2sc { sub a k by c_two_s_c; } c2sc;
feature calt { sub a l by c_a_l_t; } calt;
feature case { sub a m by c_a_s_e; } case;
feature ccmp { sub a n by c_c_m_p; } ccmp;
feature clig { sub a o by c_l_i_g; } clig;
feature cjct { sub a p by c_j_c_t; } cjct;
feature cpsp { sub a q by c_p_s_p; } cpsp;
feature cswh { sub a r by c_s_w_h; } cswh;
feature curs { sub a s by c_u_r_s; } curs;
feature dflt { sub a t by d_f_l_t; } dflt;
feature dist { sub a u by d_i_s_t; } dist;
feature dlig { sub a v by d_l_i_g; } dlig;
feature dnom { sub a w by d_n_o_m; } dnom;
feature expt { sub a x by e_x_p_t; } expt;
feature falt { sub a y by f_a_l_t; } falt;
feature fin2 { sub a z by f_i_n_two; } fin2;
feature fin3 { sub b a by f_i_n_three; } fin3;
feature fina { sub b b by f_i_n_a; } fina;
feature frac { sub b c by f_r_a_c; } frac;
feature fwid { sub b d by f_w_i_d; } fwid;
feature half { sub b e by h_a_l_f; } half;
feature haln { sub b f by h_a_l_n; } haln;
feature halt { sub b g by h_a_l_t; } halt;
feature hist { sub b h by h_i_s_t; } hist;
feature hkna { sub b i by h_k_n_a; } hkna;
feature hlig { sub b j by h_l_i_g; } hlig;
feature hngl { sub b k by h_n_g_l; } hngl;
feature hojo { sub b l by h_o_j_o; } hojo;
feature hwid { sub b m by h_w_i_d; } hwid;
feature init { sub b n by i_n_i_t; } init;
feature isol { sub b o by i_s_o_l; } isol;
feature ital { sub b p by i_t_a_l; } ital;
feature jalt { sub b q by j_a_l_t; } jalt;
feature jp78 { sub b r by j_p_seven_eight; } jp78;
feature jp83 { sub b s by j_p_eight_three; } jp83;
feature jp90 { sub b t by j_p_nine_zero; } jp90;
feature jp04 { sub b u by j_p_zero_four; } jp04;
feature kern { sub b v by k_e_r_n; } kern;
feature lfbd { sub b w by l_f_b_d; } lfbd;
feature liga { sub b x by l_i_g_a; } liga;
feature ljmo { sub b y by l_j_m_o; } ljmo;
feature lnum { sub b z by l_n_u_m; } lnum;
feature locl { sub c a by l_o_c_l; } locl;
feature mark { sub c b by m_a_r_k; } mark;
feature med2 { sub c c by m_e_d_two; } med2;
feature medi { sub c d by m_e_d_i; } medi;
feature mgrk { sub c e by m_g_r_k; } mgrk;
feature mkmk { sub c f by m_k_m_k; } mkmk;
feature mset { sub c g by m_s_e_t; } mset;
feature nalt { sub c h by n_a_l_t; } nalt;
feature nlck { sub c i by n_l_c_k; } nlck;
feature nukt { sub c j by n_u_k_t; } nukt;
feature numr { sub c k by n_u_m_r; } numr;
feature onum { sub c l by o_n_u_m; } onum;
feature opbd { sub c m by o_p_b_d; } opbd;
feature ordn { sub c n by o_r_d_n; } ordn;
feature ornm { sub c o by o_r_n_m; } ornm;
feature palt { sub c p by p_a_l_t; } palt;
feature pcap { sub c q by p_c_a_p; } pcap;
feature pnum { sub c r by p_n_u_m; } pnum;
feature pref { sub c s by p_r_e_f; } pref;
feature pres { sub c t by p_r_e_s; } pres;
feature pstf { sub c u by p_s_t_f; } pstf;
feature psts { sub c v by p_s_t_s; } psts;
feature pwid { sub c w by p_w_i_d; } pwid;
feature qwid { sub c x by q_w_i_d; } qwid;
feature rand { sub c y by r_a_n_d; } rand;
feature rkrf { sub c z by r_k_r_f; } rkrf;
feature rlig { sub d a by r_l_i_g; } rlig;
feature rphf { sub d b by r_p_h_f; } rphf;
feature rtbd { sub d c by r_t_b_d; } rtbd;
feature rtla { sub d d by r_t_l_a; } rtla;
feature ruby { sub d e by r_u_b_y; } ruby;
feature salt { sub d f by s_a_l_t; } salt;
feature sinf { sub d g by s_i_n_f; } sinf;
feature size { sub d h by s_i_z_e; } size;
feature smcp { sub d i by s_m_c_p; } smcp;
feature smpl { sub d j by s_m_p_l; } smpl;
feature ss01 { sub d k by s_s_zero_one; } ss01;
feature ss02 { sub d l by s_s_zero_two; } ss02;
feature ss03 { sub d m by s_s_zero_three; } ss03;
feature ss04 { sub d n by s_s_zero_four; } ss04;
feature ss05 { sub d o by s_s_zero_five; } ss05;
feature ss06 { sub d p by s_s_zero_six; } ss06;
feature ss07 { sub d q by s_s_zero_seven; } ss07;
feature ss08 { sub d r by s_s_zero_eight; } ss08;
feature ss09 { sub d s by s_s_zero_nine; } ss09;
feature ss10 { sub d t by s_s_one_zero; } ss10;
feature ss11 { sub d u by s_s_one_one; } ss11;
feature ss12 { sub d v by s_s_one_two; } ss12;
feature ss13 { sub d w by s_s_one_three; } ss13;
feature ss14 { sub d x by s_s_one_four; } ss14;
feature ss15 { sub d y by s_s_one_five; } ss15;
feature ss16 { sub d z by s_s_one_six; } ss16;
feature ss17 { sub e a by s_s_one_seven; } ss17;
feature ss18 { sub e b by s_s_one_eight; } ss18;
feature ss19 { sub e c by s_s_one_nine; } ss19;
feature ss20 { sub e d by s_s_two_zero; } ss20;
feature ss21 { sub e e by s_s_two_one; } ss21;
feature ss22 { sub e f by s_s_two_two; } ss22;
feature subs { sub e g by s_u_b_s; } subs;
feature sups { sub e h by s_u_p_s; } sups;
feature swsh { sub e i by s_w_s_h; } swsh;
feature titl { sub e j by t_i_t_l; } titl;
feature tjmo { sub e k by t_j_m_o; } tjmo;
feature tnam { sub e l by t_n_a_m; } tnam;
feature tnum { sub e m by t_n_u_m; } tnum;
feature trad { sub e n by t_r_a_d; } trad;
feature twid { sub e o by t_w_i_d; } twid;
feature unic { sub e p by u_n_i_c; } unic;
feature valt { sub e q by v_a_l_t; } valt;
feature vatu { sub e r by v_a_t_u; } vatu;
feature vert { sub e s by v_e_r_t; } vert;
feature vhal { sub e t by v_h_a_l; } vhal;
feature vjmo { sub e u by v_j_m_o; } vjmo;
feature vkna { sub e v by v_k_n_a; } vkna;
feature vkrn { sub e w by v_k_r_n; } vkrn;
feature vpal { sub e x by v_p_a_l; } vpal;
feature vrt2 { sub e y by v_r_t_two; } vrt2;
feature zero { sub e z by z_e_r_o; } zero;
