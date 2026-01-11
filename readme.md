# PROJETO ID - Departamento de Análise de Dados Manchester United
## Connectors
### MongoDB
- conn: mongodb+srv://<db_username>:<db_password>@projetoid.mjhpyyy.mongodb.net/
- db_username: jose db_password: jose321
- db_username:hugo db_password:hugo321
- db_username: edd db_password: edd321
- db_username: prof db_password: prof321

### MySQL
- Host: sql7.freesqldatabase.com
- Database name: sql7811781
- Database user: sql7811781
- Database password: qQUPDwhkl6
- Port number: 3306


## Data Sources
### Mongo DB
- acute_chronic_load: ac_ratio, acute_load, chronic_load, player_id, player_name, week
- gps_match_load: player_id, player_name, distance_km, hsr_m, match_date, sprints
- training_sessions: player_id, player_name, session_date, session_type, duration_min, intensity
- player_daily_status: player_id, player_name, date, status

- player_stats_creation: player,90s,age,def,def_1,fld,fld_1,gca,gca90,nation,passdead,passdead_1,passlive,passlive_1,pos,sca,sca90,sh,sh_1,to,to_1
- player_stats_defensive: player,90s,age,att,att_3rd,blocks,clr,def3rd,err,int,lost,mid3rd,nation,pass,pos,sh,tkl,tkl%,tkl_1,tkl+int,tklW
- player_stats_gk: player, #opa, #opa/90, /90,90s,age,att,att_gk,att_1,avgdist,avglen,avglen_1,ck,cmp,cmp%,fk,ga,launch%,launch%_1,nation,og,opp,pka,psxg,psxg+/-,psxg/sot,pos,stp,stp%,thr
- player_stats_misc: player, 2crdy, 90s,age,crdR,crdy,crs,fld,fls,int,lost,nation,og,off,pkcon,pkwon,pos,recov,tkiW,won,won%
- player_stats_pass_types: player,90s,age,att,blocks,ck,cmp,crs,dead,fk,in,live,nation,off,out,pos,str,sw,tb,ti
- player_stats_passing: player, 45717, 90s, a-xag, age, ast, att, att_1, att_2, att_3, cmp, cmp%, cmp%_1, cmp%_2, cmp%_3, cmp_1,cmp_2,cmp_3, crspa, kp, nation, ppa, pos, prgdist,prgp,totdist,xa,xag
- player_stats_playing_time: player, +/-, +/-90,90s,age,compl,mp,min,min%,mn/mp,mn/start,mn/sub,nation,on-off,on-off,ppm,pos,starts,subs,ong,onga,onxg,onxga,unsub,xg+/-,xg+/-90
- player_stats_possession: player, 45717, 90s, age, att, att_3rd, att_pen, cpa, carries, def_3rd, def_pen, dis, live, mid_3rd, mis, nation, pos, prgc, prgc, prgdist, prgr, rec, succ, succ%, tkld, tkld%, totdist, touches
- player_stats_shooting: player, 90s,age, dist, fk, g-xg, g/sh, g/sot, gls, nation, pk, pkatt, pos, sh, sh/90, sot, sot%, sot/90, np:g-xg,npxg, xpxg/sh, xg


### MySQL
- player_info: player_id, player_slug, player_name, name_in_home_country, date_of_birth, place_of_birth, country_of_birth, height, citizenship, is_eu, position, main_position,foot,curren_club_id,current_club_name,joined,contract_expires,outfitter,social_media_url,player_agent_id, player_agent_name, contract_option,date_of_last_contract_extension, on_loan_from_club_id,on_from_club_name, contract_there_expires, second_club_url, second_club_name, third_club_url, third_club_name, fourth_club_url,fourth_club_name, date_of death

### Excel Files
- player_wages: player, nation , pos, age, weekly wages, annual wages, notes
- player_market_value: player_id, player_name, date_unix, value
- player_injuries: player_id, player_name, season_name, injury_reason, from_date, end_date, days_missed, games_missed
- match_stats: date, time, comp, round, day, venue, result, gf, ga, opponent, xg, xga, poss, attendance, captain, formation, opp formation, referee, notes

### TXT File
- dict_countries: 2letras, 3 letras, nome_inteiro