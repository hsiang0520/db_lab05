# db_lab05
db_lab05
    const rows = await conn.query('SELECT * FROM STUDENT WHERE Student_ID = ?', [studentId]);

    if (rows.length === 0) {
      console.log('查無此人');
      return;
    }