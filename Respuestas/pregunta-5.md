db.cursos.aggregate({$group: {_id: "$nivel", totalCreditos:{ $sum:1}}})
