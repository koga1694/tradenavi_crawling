# TradeNavi 크롤링
link = http://www.tradenavi.or.kr/CmsWeb/viewPage.req?idx=PG0000001769   
원하는 업종에 대한 모든 국가의 기업 정보를 크롤링합니다.   
본 코드는 가공식품에 한정됐지만    
    # 업종 목록    
    driver.find_element(By.XPATH, '/html/body/div[2]/div[2]/div[1]/div[2]/form/div[2]/ul/li[1]/dl/dd/div/span').click()    
    위 코드에서 원하는 업종 목록으로 변경하시면 다른 업종에 대한 크롤링이 가능합니다.   
    
홈페이지가 많이 느린편이니 sleep은 그대로 두시는걸 추천드립니다.
