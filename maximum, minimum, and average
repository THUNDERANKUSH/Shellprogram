read -p "Enter Size:" N
i=1
max=0
sum=0
min=0

echo "Enter Numbers: "

while [ $i -le $N ]
do
  read num
  if [ $i -eq 1 ]
  then
      max=$num
  else
      if [ $num -gt $max ]
      then
       max=$num
      fi
  fi
  if [ $i -eq 1 ]
  then
      min=$num
  else
      if [ $num -lt $min ]
      then
       min=$num
      fi
  fi
  sum=$((sum + num))
  i=$((i + 1))
done
avg=$(echo $sum / $N | bc -l)
echo "Maximum: "$max
echo "Minimum: "$min
echo "Average: "$avg
