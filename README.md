def my_collect(array)
  i = 0

  array2 = []
  while i < array.length
    yield array2.push(array[i])
    i += 1
  end

  array2
end
