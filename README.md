# SQL_LEN
SELECT CONCAT_WS('--', PRICE, RATING) AS PRICE_PERFORMANCE,*FROM PRODUCT
WHERE SUBSTRING(PRODUCT_LINE,LEN(PRODUCT_LINE),1)='Y'
